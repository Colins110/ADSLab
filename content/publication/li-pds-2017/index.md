---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'PDS: An I/O-Efficient Scaling Scheme for Parity Declustered Data Layout'
subtitle: ''
summary: ''
authors:
- Zhipeng Li
- Yinlong Xu
- Yongkun Li
- Chengjin Tian
- Youhui Bai
tags:
- '"Algorithm design and analysis"'
- '"Arrays"'
- '"balanced incomplete block design"'
- '"Bandwidth"'
- '"BIBD"'
- '"data layout"'
- '"data migrations"'
- '"erasure coded storage systems"'
- '"High performance computing"'
- '"I/O-efficient scaling scheme"'
- '"Layout"'
- '"Linux Kernel"'
- '"parity declustering scaling"'
- '"pattern clustering"'
- '"PDS"'
- '"Performance evaluation"'
- '"RAID"'
- '"RAID performance"'
- '"redundant arrays of inexpensive disks"'
- '"Reliability"'
- '"storage management"'
categories: []
date: '2017-08-01'
lastmod: 2020-10-16T11:09:14+08:00
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
publishDate: '2020-10-16T03:09:13.784230Z'
publication_types:
- '1'
abstract: Parity declustering is widely deployed in erasure coded storage systems
  so as to provide fast recovery and high data availability. However, to perform scaling
  on such RAIDs, it is necessary to preserve the parity declustered data layout so
  as to guarantee the RAID performance after scaling. Unfortunately, existing scaling
  algorithms fail to achieve this goal so they can not be applied for scaling RAIDs
  which have deployed parity declustering. To address this challenge, we develop an
  efficient scaling algorithm called PDS (Parity Declustering Scaling). In particular,
  we first employ an auxiliary Balanced Incomplete Block Design (BIBD) to define the
  data migrations during scaling so as to preserve parity declustered data layout,
  and then define the addressing algorithm in the scaled system based on the migrations.
  We provide theoretical proofs to show that PDS preserves the parity declustered
  data layout, which is the basis for scaling RAIDs with parity declustering, and
  also theoretically prove that PDS achieves the even distribution of data/parity
  blocks after scaling and requires only the minimal data migrations. To show the
  performance of PDS, we implement it in MD in Linux Kernel, and conduct experiments
  with real-world traces. Results show PDS can reduce 89.70% of data migration time
  and 24.44% of user response time during scaling on average, compared with the round-robin
  scheme.
publication: '*2017 46th International Conference on Parallel Processing (ICPP)*'
doi: 10.1109/ICPP.2017.49
---
