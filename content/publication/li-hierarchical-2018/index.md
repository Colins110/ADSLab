---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Hierarchical RAID Architecture Towards Fast Recovery and High Reliability
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Neng Wang
- Chengjin Tian
- Si Wu
- Yueming Zhang
- Yinlong Xu
tags:
- '"balanced incomplete block design"'
- '"Bandwidth"'
- '"BIBD"'
- '"complete graph"'
- '"data reliability"'
- '"disk failure recovery"'
- '"disk failures"'
- '"disk grouping technique"'
- '"encoding"'
- '"failed disk"'
- '"fast failure recovery"'
- '"fast recovery"'
- '"fault tolerance"'
- '"Fault tolerant systems"'
- '"hierarchical code architecture"'
- '"hierarchical RAID architecture"'
- '"high system reliability"'
- '"inexpensive disks"'
- '"inner layer code"'
- '"Layout"'
- '"modern storage systems"'
- '"OI-RAID"'
- '"outer layer code"'
- '"RAID"'
- '"RAID5"'
- '"recovery process"'
- '"Redundancy"'
- '"Reed-Solomon codes"'
- '"system recovery"'
categories: []
date: '2018-04-01'
lastmod: 2020-10-16T11:09:26+08:00
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
publishDate: '2020-10-16T03:09:26.445500Z'
publication_types:
- '2'
abstract: Disk failures are very common in modern storage systems due to the large
  number of inexpensive disks. As a result, it takes a long time to recover a failed
  disk due to its large capacity and limited I/O. To speed up the recovery process
  and maintain a high system reliability, we propose a hierarchical code architecture
  with erasure codes, OI-RAID, which consists of two layers of codes, outer layer
  code and inner layer code. Specifically, the outer layer code is deployed with disk
  grouping technique based on Balanced Incomplete Block Design (BIBD) or complete
  graph with skewed data layout to provide efficient parallel I/O of all disks for
  fast failure recovery, and the inner layer code is deployed within each group of
  disks to provide high reliability. As an example, we deploy RAID5 in both layers
  to achieve fault tolerance of at least three disk failures, which meets the requirement
  of data availability in practical systems, as well as much higher speed up ratio
  for disk failure recovery than existing approaches. Besides, OI-RAID also keeps
  the optimal data update complexity and incurs low storage overhead in practice.
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2017.2775231
---
