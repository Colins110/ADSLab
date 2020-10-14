---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "分布式存储系统"
summary: "研究分布式场景下的存储问题，主要是对于分布式存储系统、分布式文件系统的问题优化"
#authors: []
tags: []
categories: []
date: 2020-10-14T16:21:58+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
# 分布式存储系统
## 背景
多年来，存储数据已经发生变化，以满足公司和个人的需求。由于技术和经济原因，我们现在正处于一个临界点，传统的存储方法 – 使用独立的专用存储盒 – 不再有效。我们不仅需要更快的驱动器和网络，我们还需要一种新的方法，即进行数据存储的新概念。多年来，这个概念以不同的形式和形状出现。虽然没有普遍接受的分布式存储系统定义，但我们可以将其概括为：“将数据存储在众多标准服务器上，尽管数据是在这些服务器之间分配的，但它们仍然作为一个存储系统运行。”分布式存储系统（DSS）是“软件定义存储”概念的高级形式。

分布式缓存当前CephFS的数据和元数据都是存储在Ceph的RADOS集群上，存在下述的一些问题：  
数据存储会使用EC池，EC存在很大的写放大问题。  
MDS当前存储的Journal和数据存储Omap机制，受限于Journal的写入性能，会导致MDS在元数据更新操作的延时比较高其整体吞吐性能比较差，并且后续的刷写OMap的性能也比较差，会使得存储的脏数据比较大，为冷启动的replay过程造成很大压力。  
小IO的场景下EC的性能非常严重，需要通过聚合IO来提升系统的整体性能。  
当前的多MDS的场景中，MDS间的数据迁移是采用MDS的缓存数据迁移（内存中），然后通过2PC的方式来完成节点的迁移，而这样的实现方式会导致处理过于复杂。  

针对上述的问题，提出下面的一些分布式缓存的设计目标：  
解决小IO的EC写放大问题  
当前Ceph的IO路径过长，整体IOPS性能偏低，能够通过缓存提供系统的整体IOPS  
提升MDS的元数据事务处理性能，可以通过元数据的写事务的优化加速  
提升MDS的读性能处理，优化数据加载的策略和数据从RADOS加载时的读性能的处理。  

## 分布式预取
