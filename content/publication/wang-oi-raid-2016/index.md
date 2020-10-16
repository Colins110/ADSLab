---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'OI-RAID: A Two-Layer RAID Architecture towards Fast Recovery and High Reliability'
subtitle: ''
summary: ''
authors:
- Neng Wang
- Yinlong Xu
- Yongkun Li
- Si Wu
tags:
- '"balanced incomplete block design"'
- '"Bandwidth"'
- '"BIBD"'
- '"codes"'
- '"Computer architecture"'
- '"Data Reliability"'
- '"disc storage"'
- '"disk failures"'
- '"disk grouping"'
- '"erasure code"'
- '"failure recovery"'
- '"fast recovery"'
- '"Fast Recovery"'
- '"hierarchical architecture"'
- '"High performance computing"'
- '"high reliability"'
- '"inner layer code"'
- '"Layout"'
- '"OI-RAID"'
- '"outer layer code"'
- '"parallel I/O efficiency"'
- '"parallel processing"'
- '"performance analysis"'
- '"performance evaluation"'
- '"RAID"'
- '"Redundancy"'
- '"Reed-Solomon codes"'
- '"Storage Architecture"'
- '"storage systems"'
- '"system recovery"'
categories: []
date: '2016-06-01'
lastmod: 2020-10-16T11:09:16+08:00
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
publishDate: '2020-10-16T03:09:16.414231Z'
publication_types:
- '1'
abstract: A lot of inexpensive disks in modern storage systems induce frequent disk
  failures. It takes a long time to recover a failed disk due to its large capacity
  and limited I/O. This paper proposes a hierarchical architecture of erasure code,
  OI-RAID. OI-RAID consists of two layers of codes, outer layer code and inner layer
  code. The outer layer code is based on disk grouping and Balanced Incomplete Block
  Design (BIBD) with skewed data layout to provide efficient parallel I/O of all disks
  for failure recovery. Inner layer code is deployed within a group of disks. As an
  example, we deploy RAID5 in both layers and present detailed performance analysis.
  With RAID5 in both layers, OI-RAID tolerates at least three disk failures meeting
  practical data availability, and achieves much higher speed up of disk failure recovery
  than existing approaches, while keeping optimal data update complexity and practically
  low storage overhead.
publication: '*2016 46th Annual IEEE/IFIP International Conference on Dependable Systems
  and Networks (DSN)*'
doi: 10.1109/DSN.2016.15
---
