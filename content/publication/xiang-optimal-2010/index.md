---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Optimal recovery of single disk failure in RDP code storage systems
subtitle: ''
summary: ''
authors:
- Liping Xiang
- Yinlong Xu
- John C.S. Lui
- Qian Chang
tags:
- '"recovery algorithm"'
- '"disk failure"'
- '"raid recovery"'
- '"RDP code"'
categories: []
date: '2010-06-01'
lastmod: 2020-12-27T11:32:01+08:00
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
publishDate: '2020-12-27T03:32:01.031267Z'
publication_types:
- '2'
abstract: 'Modern storage systems use thousands of inexpensive disks to meet the storage
  requirement of applications. To enhance the data availability, some form of redundancy
  is used. For example, conventional RAID-5 systems provide data availability for
  single disk failure only, while recent advanced coding techniques such as row-diagonal
  parity (RDP) can provide data availability with up to two disk failures. To reduce
  the probability of data unavailability, whenever a single disk fails, disk recovery
  (or rebuild) will be carried out. We show that conventional recovery scheme of RDP
  code for a single disk failure is inefficient and suboptimal. In this paper, we
  propose an optimal and efficient disk recovery scheme, Row-Diagonal Optimal Recovery
  (RDOR), for single disk failure of RDP code that has the following properties: (1)
  it is read optimal in the sense that it issues the smallest number of disk reads
  to recover the failed disk; (2) it has the load balancing property that all surviving
  disks will be subjected to the same amount of additional workload in rebuilding
  the failed disk. We carefully explore the design state space and theoretically show
  the optimality of RDOR. We carry out performance evaluation to quantify the merits
  of RDOR on some widely used disks.'
publication: '*ACM SIGMETRICS Performance Evaluation Review*'
url_pdf: https://doi.org/10.1145/1811099.1811054
doi: 10.1145/1811099.1811054
---
