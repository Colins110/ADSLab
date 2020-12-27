---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'A Hybrid Approach to Failed Disk Recovery Using RAID-6 Codes: Algorithms and
  Performance Evaluation'
subtitle: ''
summary: ''
authors:
- Liping Xiang
- Yinlong Xu
- John C. S. Lui
- Qian Chang
- Yubiao Pan
- Runhui Li
tags:
- '"recovery algorithm"'
- '"RDP code"'
- '"Disk failure"'
- '"EVENODD code"'
- '"RAID recovery"'
categories: []
date: '2011-10-01'
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
publishDate: '2020-12-27T03:32:02.686733Z'
publication_types:
- '2'
abstract: 'The current parallel storage systems use thousands of inexpensive disks
  to meet the storage requirement of applications. Data redundancy and/or coding are
  used to enhance data availability, for instance, Row-diagonal parity (RDP) and EVENODD
  codes, which are widely used in RAID-6 storage systems, provide data availability
  with up to two disk failures. To reduce the probability of data unavailability,
  whenever a single disk fails, disk recovery will be carried out. We find that the
  conventional recovery schemes of RDP and EVENODD codes for a single failed disk
  only use one parity disk. However, there are two parity disks in the system, and
  both can be used for single disk failure recovery. In this article, we propose a
  hybrid recovery approach that uses both parities for single disk failure recovery,
  and we design efficient recovery schemes for RDP code (RDOR-RDP) and EVENODD code
  (RDOR-EVENODD). Our recovery scheme has the following attractive properties: (1)
  “read optimality” in the sense that our scheme issues the smallest number of disk
  reads to recover a single failed disk and it reduces approximately 1/4 of disk reads
  compared with conventional schemes; (2) “load balancing property” in that all surviving
  disks will be subjected to the same (or almost the same) amount of additional workload
  in rebuilding the failed disk. We carry out performance evaluation to quantify the
  merits of RDOR-RDP and RDOR-EVENODD on some widely used disks with DiskSim. The
  offline experimental results show that RDOR-RDP and RDOR-EVENODD outperform the
  conventional recovery schemes of RDP and EVENODD codes in terms of total recovery
  time and recovery workload on individual surviving disk. However, the improvements
  are less than the theoretical value (approximately 25%), as RDOR-RDP and RDOR-EVENODD
  change the disk access pattern from purely sequential to a more random one compared
  with their conventional schemes.'
publication: '*ACM Transactions on Storage*'
url_pdf: https://doi.org/10.1145/2027066.2027071
doi: 10.1145/2027066.2027071
---
