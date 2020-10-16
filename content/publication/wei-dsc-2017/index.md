---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'DSC: Dynamic stripe construction for asynchronous encoding in clustered file
  system'
subtitle: ''
summary: ''
authors:
- Shuzhan Wei
- Yongkun Li
- Yinlong Xu
- Si Wu
tags:
- '"asynchronous encoding"'
- '"bounded storage overhead"'
- '"clustered file system"'
- '"coding stripes"'
- '"cross-rack traffic"'
- '"data availability"'
- '"data block redistribution"'
- '"data layouts"'
- '"Distributed databases"'
- '"distributed file system"'
- '"DSC"'
- '"Dynamic stripe construction"'
- '"Dynamic Stripe Construction"'
- '"Ear"'
- '"encoding"'
- '"Encoding"'
- '"encoding throughput"'
- '"erasure codes"'
- '"erasure coding"'
- '"Fault tolerance"'
- '"Fault tolerant systems"'
- '"foreground user response time"'
- '"Layout"'
- '"logically sequential data blocks"'
- '"N-way replication"'
- '"replicated data blocks"'
- '"storage cluster"'
- '"storage management"'
categories: []
date: '2017-05-01'
lastmod: 2020-10-16T11:09:13+08:00
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
publishDate: '2020-10-16T03:09:13.432229Z'
publication_types:
- '1'
abstract: Nowadays many clustered file systems adopt asynchronous encoding which transforms
  replicated data into erasure coding to maintain data availability with bounded storage
  overhead. Existing implementations of asynchronous encoding construct coding stripes
  with logically sequential data blocks, which suffers from heavy cross-rack traffic
  and necessitates data block redistribution. Recent work [12] solves this problem
  by carefully distributing replicated data blocks among racks at the time when they
  are being written, but it is not applicable to the cases when existing systems have
  different data layouts or the data layout changes. In this paper, we propose Dynamic
  Stripe Construction (DSC) to transform N-way replication to erasure coding. DSC
  does not induce to any cross-rack traffic for encoding, and it does not require
  data block redistribution after encoding. Besides, DSC is general enough to be applied
  to any existing CFSes with various erasure codes, and it can also be deployed on
  a distributed file system in a hot-plugging-in manner. To validate the effectiveness
  of DSC, we implement it on HDFS. Through extensive testbed experiments in a real
  storage cluster, we show that DSC can significantly increase the encoding throughput
  and reduce the foreground user response time over the traditional approach.
publication: '*IEEE INFOCOM 2017 - IEEE Conference on Computer Communications*'
doi: 10.1109/INFOCOM.2017.8056998
---
