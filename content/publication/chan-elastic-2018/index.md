---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Elastic Parity Logging for SSD RAID Arrays: Design, Analysis, and Implementation'
subtitle: ''
summary: ''
authors:
- Helen H. W. Chan
- Yongkun Li
- Patrick P. C. Lee
- Yinlong Xu
tags:
- '"Arrays"'
- '"elastic parity logging"'
- '"Encoding"'
- '"EPLOG prototype"'
- '"flash memories"'
- '"garbage collection operations"'
- '"I/O throughput"'
- '"input-output programs"'
- '"large-scale SSD storage systems"'
- '"Linux"'
- '"Linux software RAID implementation"'
- '"meta data"'
- '"parity logging"'
- '"parity-based RAID"'
- '"Performance evaluation"'
- '"Prototypes"'
- '"RAID"'
- '"reliability"'
- '"reliability analysis"'
- '"Reliability engineering"'
- '"Software"'
- '"SSD"'
- '"SSD failures"'
- '"SSD RAID arrays"'
- '"storage layer"'
- '"storage management"'
- '"trace-driven testbed experiments"'
categories: []
date: '2018-10-01'
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
publishDate: '2020-10-16T03:09:25.542501Z'
publication_types:
- '2'
abstract: 'Parity-based RAID poses a design trade-off issue for large-scale SSD storage
  systems: it improves reliability against SSD failures through redundancy, yet its
  parity updates incur extra I/Os and garbage collection operations, thereby degrading
  the endurance and performance of SSDs. We propose EPLOG, a storage layer that reduces
  parity traffic to SSDs, so as to provide endurance, reliability, and performance
  guarantees for SSD RAID arrays. EPLOG mitigates parity update overhead via elastic
  parity logging, which redirects parity traffic to separate log devices (to improve
  endurance and reliability) and eliminates the need of pre-reading data in parity
  computations (to improve performance). We design EPLOG as a user-level implementation
  that is fully compatible with commodity hardware and general erasure coding schemes.
  We evaluate EPLOG through reliability analysis and trace-driven testbed experiments.
  Compared to the Linux software RAID implementation, our experimental results show
  that our EPLOG prototype reduces the total write traffic to SSDs, reduces the number
  of garbage collection operations, and increases the I/O throughput. In addition,
  EPLOG significantly improves the I/O performance over the original parity logging
  design, and incurs low metadata overhead.'
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2018.2818171
---
