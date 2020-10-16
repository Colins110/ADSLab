---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Grouping-Based Elastic Striping with Hotness Awareness for Improving SSD RAID
  Performance
subtitle: ''
summary: ''
authors:
- Yubiao Pan
- Yongkun Li
- Yinlong Xu
- Zhipeng Li
tags:
- '"Arrays"'
- '"Delays"'
- '"Elastic Striping"'
- '"Endurance"'
- '"Fault tolerance"'
- '"Fault tolerant systems"'
- '"grouping-based elastic striping"'
- '"hotness awareness"'
- '"Performance"'
- '"Performance evaluation"'
- '"Prototypes"'
- '"RAID"'
- '"RAID-level garbage collection"'
- '"RAID-level Garbage Collection"'
- '"read-modify-write"'
- '"read-reconstruct-write"'
- '"rewriting systems"'
- '"SSD RAID"'
- '"storage management"'
- '"Time factors"'
categories: []
date: '2015-06-01'
lastmod: 2020-10-16T11:09:22+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-10-16T03:09:22.146382Z'
publication_types:
- '1'
abstract: RAID provides a good option to provide device-level fault tolerance. Conventional
  RAID usually updates parities with read-modify-write or read-reconstruct-write,
  which may introduce a lot of extra I/Os and thus significantly degrade SSD RAID
  performance. The recently proposed elastic striping scheme reconstructs new stripes
  with updated new data chunks without updating old parity chunks. However, it necessitates
  RAID-level garbage collection which may incur a very high cost. In this paper, we
  propose a hotness-aware caching scheme to buffer incoming writes and categorize
  data chunks in buffers into multiple groups according to their hotness values. We
  then propose a grouping-based elastic striping scheme to separately write data chunks
  in different groups into SSDs. We deployed the proposed schemes on a RAID-5 array
  composed of eight commercial SSDs, and experimental results show that compared to
  elastic striping, our scheme reduces 26% – 65% of chunk writes to SSDs, and also
  reduces the average response time by 17.2% – 63.9%.
publication: '*2015 45th Annual IEEE/IFIP International Conference on Dependable Systems
  and Networks*'
doi: 10.1109/DSN.2015.51
---
