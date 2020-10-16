---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'FlameDB: A Key-Value Store With Grouped Level Structure and Heterogeneous
  Bloom Filter'
subtitle: ''
summary: ''
authors:
- Weitao Zhang
- Yinlong Xu
- Yongkun Li
- Yueming Zhang
- Dinglong Li
tags:
- '"bloom filter"'
- '"Compaction"'
- '"external storage"'
- '"FlameDB"'
- '"GLS"'
- '"Google"'
- '"grouped level structure"'
- '"HEBF"'
- '"Heterogeneous Bloom Filter"'
- '"I/O resources"'
- '"Indexes"'
- '"Information filters"'
- '"Key-value"'
- '"key-value store"'
- '"log-structured merge-tree"'
- '"LSM-tree based KV store"'
- '"read amplification"'
- '"Relational databases"'
- '"SQL"'
- '"SQL databases"'
- '"storage management"'
- '"Throughput"'
- '"tree data structures"'
- '"write amplification"'
categories: []
date: '2018-01-01'
lastmod: 2020-10-16T11:09:26+08:00
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
publishDate: '2020-10-16T03:09:26.063500Z'
publication_types:
- '2'
abstract: Key-value (KV) stores are widely used to provide much higher read and write
  throughput than traditional SQL databases. In particular, LSM-tree based KV store
  is popular with many applications since it could eliminate random writes and thus
  provides good write performance. However, the data residing in external storage
  are compacted from time to time, which takes a large amount of I/O resources and
  degrades the system performance. In this paper, we propose FlameDB, which leverages
  grouped level structure (GLS) to mitigate the compaction overhead. Besides dividing
  the whole storage space into multiple components as in LSM-tree, GLS further divides
  each component into multiple groups and compacts all KV items in a component as
  a group of the next component. Besides, we also propose a heterogeneous bloom filter
  (HEBF) scheme which assigns more bits to the bloom filters in upper components.
  With HEBF, the false positive rate of a bloom filter in upper components become
  smaller, and this scheme reduces the expected number of I/Os to read a KV item from
  the external storage with a given memory usage. Our experiments show that FlameDB
  saves about 75% I/O during compaction, so it improves the write throughput by about
  four times. Meanwhile, the read performance is also slightly improved by deploying
  HEBF.
publication: '*IEEE Access*'
doi: 10.1109/ACCESS.2018.2831259
---
