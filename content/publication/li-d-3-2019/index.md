---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'D3: Deterministic Data Distribution for Efficient Data Reconstruction in Erasure-Coded
  Distributed Storage Systems'
subtitle: ''
summary: ''
authors:
- Zhipeng Li
- Min Lv
- Yinlong Xu
- Yongkun Li
- Liangliang Xu
tags:
- '"Arrays"'
- '"Bandwidth"'
- '"cross-rack repair traffic"'
- '"data handling"'
- '"data layout"'
- '"data layouts"'
- '"data reconstruction"'
- '"data reliability"'
- '"data storage"'
- '"deterministic data distribution"'
- '"Distributed databases"'
- '"erasure codes"'
- '"erasure-coded distributed storage systems"'
- '"failure recovery process"'
- '"fast recovery"'
- '"Fault tolerance"'
- '"Fault tolerant systems"'
- '"Hadoop Distributed File System"'
- '"heavy crossrack traffic"'
- '"large-scale distributed storage systems"'
- '"Layout"'
- '"Maintenance engineering"'
- '"network operating systems"'
- '"parallel processing"'
- '"random data placement"'
- '"storage management"'
- '"storage servers"'
- '"system recovery"'
categories: []
date: '2019-05-01'
lastmod: 2020-10-16T11:09:07+08:00
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
publishDate: '2020-10-16T03:09:07.533233Z'
publication_types:
- '1'
abstract: Due to individual unreliable commodity components, failures are common in
  large-scale distributed storage systems. Erasure codes are widely deployed in practical
  storage systems to provide fault tolerance with low storage overhead. However, the
  commonly used random data placement in storage systems based on erasure codes induces
  to heavy crossrack traffic, load imbalance, and random access, which slow down the
  recovery process upon failures. In this paper, with orthogonal arrays, we define
  a Deterministic Data Distribution (D3) of blocks to nodes and racks, and propose
  an efficient failure recovery approach based on D3. D3 not only uniformly distributes
  data/parity blocks among storage servers, but also balances the repair traffic among
  racks and storage servers for failure recovery. Furthermore, D3 also minimizes the
  cross-rack repair traffic for data layouts against a single rack failure and provides
  sequential access for failure recovery. We implement D3 in Hadoop Distributed File
  System (HDFS) with a cluster of 28 machines. Our experiments show that D3 significantly
  speeds up the failure recovery process compared with random data distribution, e.g.,
  2.21 times for (6, 3)-RS code in a system consisting of eight racks and three nodes
  in each rack.
publication: '*2019 IEEE International Parallel and Distributed Processing Symposium
  (IPDPS)*'
doi: 10.1109/IPDPS.2019.00064
---
