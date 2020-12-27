---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A cost-based heterogeneous recovery scheme for distributed storage systems
  with RAID-6 codes
subtitle: ''
summary: ''
authors:
- Y. Zhu
- P. P. C. Lee
- L. Xiang
- Y. Xu
- Lingling Gao
tags:
- '"storage management"'
- '"Bandwidth"'
- '"Cloud computing"'
- '"Reliability"'
- '"Encoding"'
- '"failure recovery"'
- '"Measurement"'
- '"fault tolerance"'
- '"Optimization"'
- '"distributed storage systems"'
- '"optimization model"'
- '"node heterogeneity"'
- '"Peer to peer computing"'
- '"CHR algorithm"'
- '"cost-based heterogeneous recovery scheme"'
- '"data block minimization"'
- '"data loss recovery"'
- '"data unavailability probability reduction"'
- '"distributed processing"'
- '"distributed storage system"'
- '"experimentation"'
- '"generic costs"'
- '"global optimal solution"'
- '"heterogeneous storage devices"'
- '"large-scale fault-tolerant data storage"'
- '"minimisation"'
- '"networked storage system"'
- '"RAID- 6-coded storage systems"'
- '"RAID-6 codes"'
- '"solution space"'
- '"storage node failure"'
- '"testbed experiments"'
- '"total recovery time reduction"'
- '"transmission bandwidths"'
categories: []
date: '2012-06-01'
lastmod: 2020-12-27T11:32:02+08:00
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
publishDate: '2020-12-27T03:32:02.073594Z'
publication_types:
- '1'
abstract: Modern distributed storage systems provide large-scale, fault-tolerant data
  storage. To reduce the probability of data unavailability, it is important to recover
  the lost data of any failed storage node efficiently. In practice, storage nodes
  are of heterogeneous types and have different transmission bandwidths. Thus, traditional
  recovery solutions that simply minimize the number of data blocks being read may
  no longer be optimal in a heterogeneous environment. We propose a cost-based heterogeneous
  recovery (CHR) algorithm for RAID-6-coded storage systems. We formulate the recovery
  problem as an optimization model in which storage nodes are associated with generic
  costs. We narrow down the solution space of the model to make it practically tractable,
  while still achieving the global optimal solution in most cases. We implement different
  recovery algorithms and conduct testbed experiments on a real networked storage
  system with heterogeneous storage devices. We show that our CHR algorithm reduces
  the total recovery time of existing recovery solutions in various scenarios.
publication: '*IEEE/IFIP International Conference on Dependable Systems and Networks
  (DSN 2012)*'
doi: 10.1109/DSN.2012.6263934
---
