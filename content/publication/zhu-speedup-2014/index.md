---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: On the Speedup of Recovery in Large-Scale Erasure-Coded Storage Systems
subtitle: ''
summary: ''
authors:
- Yunfeng Zhu
- Patrick P.C. Lee
- Yinlong Xu
- Yuchong Hu
- Liping Xiang
tags:
- '"Algorithm design and analysis"'
- '"availability guarantees"'
- '"data redundancy"'
- '"Distributed databases"'
- '"Encoding"'
- '"Equations"'
- '"fast recovery solution"'
- '"fault tolerant computing"'
- '"Generators"'
- '"hill-climbing technique"'
- '"large-scale erasure-coded storage systems"'
- '"Mathematical model"'
- '"networked storage system testbed"'
- '"node failures"'
- '"parallelized architecture"'
- '"recovery algorithm"'
- '"replace recovery algorithm"'
- '"single-node failure"'
- '"single-node failure recovery"'
- '"storage management"'
- '"Strips"'
- '"vulnerability window"'
- '"XOR operations"'
- '"XOR-based erasure codes"'
- '"XOR-coded storage system"'
categories: []
date: '2014-07-01'
lastmod: 2020-10-16T11:09:33+08:00
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
publishDate: '2020-10-16T03:09:32.803500Z'
publication_types:
- '2'
abstract: Modern storage systems stripe redundant data across multiple nodes to provide
  availability guarantees against node failures. One form of data redundancy is based
  on XOR-based erasure codes, which use only XOR operations for encoding and decoding.
  In addition to tolerating failures, a storage system must also provide fast failure
  recovery to reduce the window of vulnerability. This work addresses the problem
  of speeding up the recovery of a single-node failure for general XOR-based erasure
  codes. We propose a replace recovery algorithm, which uses a hill-climbing technique
  to search for a fast recovery solution, such that the solution search can be completed
  within a short time period. We further extend the algorithm to adapt to the scenario
  where nodes have heterogeneous capabilities (e.g., processing power and transmission
  bandwidth). We implement our replace recovery algorithm atop a parallelized architecture
  to demonstrate its feasibility. We conduct experiments on a networked storage system
  testbed, and show that our replace recovery algorithm uses less recovery time than
  the conventional recovery approach.
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2013.244
---
