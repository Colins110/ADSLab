---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Workload-Aware Elastic Striping With Hot Data Identification for SSD RAID Arrays
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Biaobiao Shen
- Yubiao Pan
- Yinlong Xu
- Zhipeng Li
- John C. S. Lui
tags:
- '"Arrays"'
- '"data chunks"'
- '"device-level fault tolerance"'
- '"disc drives"'
- '"Elastic striping"'
- '"fault tolerance"'
- '"Fault tolerance"'
- '"Fault tolerant systems"'
- '"hard discs"'
- '"lightweight hot data identification scheme"'
- '"Memory management"'
- '"parity chunks"'
- '"Performance evaluation"'
- '"Prototypes"'
- '"RAID-level garbage collection process"'
- '"read-modify-write"'
- '"read-reconstruct-write"'
- '"redundant array of independent disk"'
- '"redundant array of independent disks (RAID)-level garbage collection"'
- '"solid-state drive (SSD) RAID"'
- '"solid-state drives"'
- '"SSD RAID arrays"'
- '"WAS"'
- '"workload awareness"'
- '"workload-aware elastic striping"'
- '"workload-aware scheme"'
categories: []
date: '2017-05-01'
lastmod: 2020-10-16T11:09:28+08:00
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
publishDate: '2020-10-16T03:09:28.143502Z'
publication_types:
- '2'
abstract: Redundant array of independent disk (RAID) offers a good option to provide
  device-level fault tolerance for solid-state drives (SSDs). However, parity update
  with either read-modify-write or read-reconstruct-write may introduce a lot of extra
  I/Os and thus significantly degrades SSD RAID performance. To reduce the parity
  update cost, elastic striping chooses to reconstruct new stripes with only the newly
  updated data chunks instead of directly updating parity chunks. However, it necessitates
  an RAID-level garbage collection (GC) process, which may incur a very high cost
  due to the mixture of hot and cold data chunks. To address this problem, we follow
  the idea of elastic striping and propose a workload-aware scheme (WAS) to reduce
  the RAID-level GC cost so as to improve the performance and endurance of SSD RAID.
  In particular, we first develop a novel lightweight hot data identification scheme
  which requires only a very small computation time and memory cost, then propose
  a hotness-aware elastic striping approach to separately write data chunks with different
  hotness to different regions in SSD RAID. To evaluate the effectiveness and efficiency
  of our WAS, we implement a prototype system on RAID-5 and RAID-6 arrays composed
  of commercial SSDs. Experimental results show that compared to original elastic
  striping, our scheme reduces 30.0%-70.6% (and 23.9%-63.2%) of chunk writes under
  the RAID-5 (and RAID-6) settings, and also reduces the average response time by
  60.9%-79.3% (and 56.8%-80.9%) for RAID-5 (and RAID-6), respectively. Besides, our
  scheme also improves the endurance and reliability of SSD RAID compared to original
  elastic striping.
publication: '*IEEE Transactions on Computer-Aided Design of Integrated Circuits and
  Systems*'
doi: 10.1109/TCAD.2016.2604292
---
