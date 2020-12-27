---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'On the speedup of single-disk failure recovery in XOR-coded storage systems:
  Theory and practice'
subtitle: ''
summary: ''
authors:
- Y. Zhu
- P. P. C. Lee
- Y. Hu
- L. Xiang
- Y. Xu
tags:
- '"Computational modeling"'
- '"system recovery"'
- '"Strips"'
- '"encoding"'
- '"Encoding"'
- '"Complexity theory"'
- '"disc storage"'
- '"redundancy"'
- '"data redundancy"'
- '"Equations"'
- '"Generators"'
- '"hill-climbing technique"'
- '"Mathematical model"'
- '"networked storage system testbed"'
- '"parallelized architecture"'
- '"replace recovery algorithm"'
- '"XOR-based erasure codes"'
- '"decoding"'
- '"data unavailability"'
- '"error correction codes"'
- '"failure tolerance"'
- '"parallel architectures"'
- '"recovery solution search"'
- '"recovery time"'
- '"single-disk failure recovery"'
- '"XOR-coded storage systems"'
categories: []
date: '2012-04-01'
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
publishDate: '2020-12-27T03:32:01.237866Z'
publication_types:
- '1'
abstract: Modern storage systems stripe redundant data across multiple disks to provide
  availability guarantees against disk failures. One form of data redundancy is based
  on XOR-based erasure codes, which use only XOR operations for encoding and decoding.
  In addition to providing failure tolerance, a storage system must also provide fast
  failure recovery to avoid data unavailability. We consider the problem of speeding
  up the recovery of a single-disk failure for arbitrary XOR-based erasure codes.
  We address this problem from both theoretical and practical perspectives. We propose
  a replace recovery algorithm, which uses a hill-climbing technique to search for
  a fast recovery solution, such that the solution search can be completed within
  a short time period. We further implement our replace recovery algorithm atop a
  parallelized architecture to justify its practicality. We experiment our replace
  recovery algorithm and its parallelized implementation on a networked storage system
  testbed, and demonstrate that our replace recovery algorithm uses less recovery
  time than the conventional approach.
publication: '*2012 IEEE 28th Symposium on Mass Storage Systems and Technologies (MSST)*'
doi: 10.1109/MSST.2012.6232371
---
