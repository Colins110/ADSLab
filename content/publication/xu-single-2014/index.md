---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Single Disk Failure Recovery for X-Code-Based Parallel Storage Systems
subtitle: ''
summary: ''
authors:
- Silei Xu
- Runhui Li
- Patrick P.C. Lee
- Yunfeng Zhu
- Liping Xiang
- Yinlong Xu
- John C.S. Lui
tags:
- '"Arrays"'
- '"cloud storage"'
- '"coding theory"'
- '"Complexity theory"'
- '"data availability"'
- '"data centers"'
- '"Data communication"'
- '"disc storage"'
- '"double-fault tolerant coding scheme"'
- '"encoding"'
- '"Encoding"'
- '"Load management"'
- '"logical encoding scheme"'
- '"MDRR"'
- '"minimum-disk-read-recovery"'
- '"networked storage system prototype"'
- '"optimal single-disk failure recovery"'
- '"optimal update complexity"'
- '"parallel memories"'
- '"Parallel storage systems"'
- '"Peer to peer computing"'
- '"recovery algorithm"'
- '"redundancy"'
- '"redundancy coding schemes"'
- '"reliability"'
- '"Reliability"'
- '"single disk failure recovery algorithm"'
- '"storage management"'
- '"system recovery"'
- '"X-code-based optimal recovery scheme"'
- '"X-code-based parallel storage systems"'
categories: []
date: '2014-04-01'
lastmod: 2020-10-16T11:09:31+08:00
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
publishDate: '2020-10-16T03:09:31.141501Z'
publication_types:
- '2'
abstract: In modern parallel storage systems (e.g., cloud storage and data centers),
  it is important to provide data availability guarantees against disk (or storage
  node) failures via redundancy coding schemes. One coding scheme is X-code, which
  is double-fault tolerant while achieving the optimal update complexity. When a disk/node
  fails, recovery must be carried out to reduce the possibility of data unavailability.
  We propose an X-code-based optimal recovery scheme called minimum-disk-read-recovery
  (MDRR), which minimizes the number of disk reads for single-disk failure recovery.
  We make several contributions. First, we show that MDRR provides optimal single-disk
  failure recovery and reduces about 25 percent of disk reads compared to the conventional
  recovery approach. Second, we prove that any optimal recovery scheme for X-code
  cannot balance disk reads among different disks within a single stripe in general
  cases. Third, we propose an efficient logical encoding scheme that issues balanced
  disk read in a group of stripes for any recovery algorithm (including the MDRR scheme).
  Finally, we implement our proposed recovery schemes and conduct extensive testbed
  experiments in a networked storage system prototype. Experiments indicate that MDRR
  reduces around 20 percent of recovery time of the conventional approach, showing
  that our theoretical findings are applicable in practice.
publication: '*IEEE Transactions on Computers*'
doi: 10.1109/TC.2013.8
---
