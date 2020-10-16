---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Light-Weight Hot Data Identification Scheme via Grouping-based LRU Lists
subtitle: ''
summary: ''
authors:
- Biaobiao Shen
- Yongkun Li
- Yinlong Xu
- Yubiao Pan
tags:
- '"Algorithm"'
- '"Garbage collection"'
- '"Hot data identification"'
- '"LRU"'
- '"SSD"'
categories: []
date: '2015-01-01'
lastmod: 2020-10-16T11:09:19+08:00
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
publishDate: '2020-10-16T03:09:18.854233Z'
publication_types:
- '1'
abstract: Real-world workloads generally exhibit high skewness in access patterns,
  and it is a consensus that separating hot and cold data may greatly improve storage
  system performance such as Solid State Drive(SSD) garbage collection(GC) performance.
  To achieve this, the key issue is how to accurately identify hot data, which is
  really challenging due to the large diversity and dynamics of workloads. In this
  paper, we propose a light-weight and high-accuracy identification scheme, which
  is developed via a group of Least Recently Used (LRU) lists and requires only a
  small amount of memory and CPU cycles. We further deploy our scheme on SSDs with
  DiskSim simulator, and results show that comparing to two state-of-the-art identification
  schemes, our scheme further reduces SSD GC cost by up to 59.1 % (62.1 %), and saves
  44.3 % (77.5 %) of computational cost. Due to the light-weight and parameter-insensitive
  feature, our scheme can be easily deployed at various system levels and adaptable
  to different workloads.
publication: '*Algorithms and Architectures for Parallel Processing*'
doi: 10.1007/978-3-319-27140-8_7
---
