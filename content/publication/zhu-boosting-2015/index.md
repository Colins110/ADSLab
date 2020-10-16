---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Boosting Degraded Reads in Heterogeneous Erasure-Coded Storage Systems
subtitle: ''
summary: ''
authors:
- Yunfeng Zhu
- Jian Lin
- Patrick P. C. Lee
- Yinlong Xu
tags:
- '"Bandwidth"'
- '"data redundancy"'
- '"data replication"'
- '"data transfer"'
- '"Decoding"'
- '"degraded read boosting"'
- '"degraded reads"'
- '"digital storage"'
- '"distributed storage systems"'
- '"electronic data interchange"'
- '"encoding"'
- '"Encoding"'
- '"Equations"'
- '"erasure coding"'
- '"Erasure-coded storage system"'
- '"FastDR"'
- '"frequent node failures"'
- '"Hadoop cluster"'
- '"heterogeneous erasure-coded storage systems"'
- '"I/O parallelism"'
- '"large-scale data storage services"'
- '"large-scale storage systems"'
- '"node heterogeneity"'
- '"Optimization"'
- '"Parallel processing"'
- '"Redundancy"'
categories: []
date: '2015-08-01'
lastmod: 2020-10-16T11:09:35+08:00
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
publishDate: '2020-10-16T03:09:35.063501Z'
publication_types:
- '2'
abstract: Distributed storage systems provide large-scale data storage services, yet
  they are confronted with frequent node failures. To ensure data availability, a
  storage system often introduces data redundancy via replication or erasure coding.
  As erasure coding incurs significantly less redundancy overhead than replication
  under the same fault tolerance, it has been increasingly adopted in large-scale
  storage systems. In erasure-coded storage systems, degraded reads to temporarily
  unavailable data are very common, and hence boosting the performance of degraded
  reads becomes important. One challenge is that storage nodes tend to be heterogeneous
  with different storage capacities and I/O bandwidths. To this end, we propose FastDR,
  a system that addresses node heterogeneity and exploits I/O parallelism, so as to
  boost the performance of degraded reads to temporarily unavailable data. FastDR
  incorporates a greedy algorithm that seeks to reduce the data transfer cost of reading
  surviving data for degraded reads, while allowing the search of the efficient degraded
  read solution to be completed in a timely manner. We implement a FastDR prototype,
  and conduct extensive evaluation through simulation studies as well as testbed experiments
  on a Hadoop cluster with 10 storage nodes. We demonstrate that our FastDR achieves
  efficient degraded reads compared to existing approaches.
publication: '*IEEE Transactions on Computers*'
doi: 10.1109/TC.2014.2360543
---
