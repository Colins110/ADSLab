---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Even data placement for load balance in reliable distributed deduplication
  storage systems
subtitle: ''
summary: ''
authors:
- Min Xu
- Yunfeng Zhu
- Patrick P. C. Lee
- Yinlong Xu
tags:
- '"Bandwidth"'
- '"combinatorial mathematics"'
- '"combinatorial optimization problem"'
- '"computational complexity"'
- '"content-level redundancy"'
- '"distributed processing"'
- '"distributed storage system"'
- '"EDP algorithm"'
- '"Encoding"'
- '"erasure coding"'
- '"greedy algorithms"'
- '"greedy polynomial-time even data placement algorithm"'
- '"Indexes"'
- '"load balance problem"'
- '"Optimization"'
- '"prototype testbed experiment"'
- '"Prototypes"'
- '"Quality of service"'
- '"read balance"'
- '"read performance"'
- '"Reliability"'
- '"reliable distributed deduplication storage system"'
- '"resource allocation"'
- '"round-robin placement"'
- '"storage balance"'
- '"storage efficiency"'
- '"storage management"'
- '"storage node"'
- '"unbalanced data placement"'
categories: []
date: '2015-06-01'
lastmod: 2020-10-16T11:09:22+08:00
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
publishDate: '2020-10-16T03:09:21.666369Z'
publication_types:
- '1'
abstract: Modern distributed storage systems often deploy deduplication to remove
  content-level redundancy and hence improve storage efficiency. However, deduplication
  inevitably leads to unbalanced data placement across storage nodes, thereby degrading
  read performance. This paper studies the load balance problem in the setting of
  a reliable distributed deduplication storage system, which deploys deduplication
  for storage efficiency and erasure coding for reliability. We argue that in such
  a setting, it is generally challenging to find a data placement that simultaneously
  achieves both read balance and storage balance objectives. To this end, we formulate
  a combinatorial optimization problem, and propose a greedy, polynomial-time Even
  Data Placement (EDP) algorithm, which identifies a data placement that effectively
  achieves read balance while maintaining storage balance. We further extend our EDP
  algorithm to heterogeneous environments. We demonstrate the effectiveness of our
  EDP algorithm under real-world workloads using both extensive simulations and prototype
  testbed experiments. In particular, our testbed experiments show that our EDP algorithm
  reduces the file read time by 37.41% compared to the baseline round-robin placement,
  and the reduction can further reach 52.11% in a heterogeneous setting.
publication: '*2015 IEEE 23rd International Symposium on Quality of Service (IWQoS)*'
doi: 10.1109/IWQoS.2015.7404754
---
