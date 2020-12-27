---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Deterministic Data Distribution for Efficient Recovery in Erasure-Coded Storage
  Systems
subtitle: ''
summary: ''
authors:
- L. Xu
- M. Lyu
- Z. Li
- Y. Li
- Y. Xu
tags:
- '"Fault tolerant systems"'
- '"storage management"'
- '"Arrays"'
- '"Bandwidth"'
- '"file organisation"'
- '"cross-rack repair traffic"'
- '"deterministic data distribution"'
- '"erasure codes"'
- '"Fault tolerance"'
- '"large-scale distributed storage systems"'
- '"Layout"'
- '"Maintenance engineering"'
- '"network operating systems"'
- '"parallel processing"'
- '"system recovery"'
- '"cross-rack traffic"'
- '"erasure coding"'
- '"Reed-Solomon codes"'
- '"distributed databases"'
- '"Distributed storage system"'
- '"erasure-coded storage systems"'
- '"failure recovery approach"'
- '"fault tolerant computing"'
- '"Hadoop distributed file system"'
- '"load balance"'
- '"locally repairable codes"'
- '"orthogonal array"'
- '"random data distribution"'
- '"RDD"'
- '"storage overhead"'
- '"telecommunication network reliability"'
- '"telecommunication traffic"'
- '"traffic"'
categories: []
date: '2020-10-01'
lastmod: 2020-12-27T11:32:00+08:00
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
publishDate: '2020-12-27T03:32:00.002793Z'
publication_types:
- '2'
abstract: Due to individual unreliable commodity components, failures are common in
  large-scale distributed storage systems. Erasure codes are widely deployed in practical
  storage systems to provide fault tolerance with low storage overhead. However, random
  data distribution (RDD), commonly used in erasure-coded storage systems, induces
  heavy cross-rack traffic, load imbalance, and random access, which adversely affects
  failure recovery. In this article, with orthogonal arrays, we define a Deterministic
  Data Distribution (D3) to uniformly distribute data/parity blocks among nodes, and
  propose an efficient failure recovery approach based on D3, which minimizes the
  cross-rack repair traffic against a single node failure. Thanks to the uniformity
  of D3, the proposed recovery approach balances the repair traffic not only among
  nodes within a rack but also among racks. We implement D3 over Reed-Solomon codes
  and Locally Repairable Codes in Hadoop Distributed File System (HDFS) with a cluster
  of 28 machines. Compared with RDD, our experiments show that D3 significantly speeds
  up the failure recovery up to 2.49 times for RS codes and 1.38 times for LRCs. Moreover,
  D3 supports front-end applications better than RDD in both of normal and recovery
  states.
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2020.2987837
---
