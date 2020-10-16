---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Improving Write Performance of LSMT-Based Key-Value Store
subtitle: ''
summary: ''
authors:
- Weitao Zhang
- Yinlong Xu
- Yongkun Li
- Dinglong Li
tags:
- '"Compaction"'
- '"compaction I/O overhead"'
- '"data structures"'
- '"grouped level structure"'
- '"High performance computing"'
- '"Indexes"'
- '"Key-Value"'
- '"Layout"'
- '"log structure merge tree"'
- '"Log Structured Merge Tree"'
- '"LSMT-based key-value store"'
- '"Micromechanical devices"'
- '"Throughput"'
- '"write performance"'
categories: []
date: '2016-12-01'
lastmod: 2020-10-16T11:09:15+08:00
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
publishDate: '2020-10-16T03:09:14.993231Z'
publication_types:
- '1'
abstract: Key-value stores are widely used to provide much higher read and write throughput
  than traditional SQL databases. LSMT (log structure merge tree) based key-value
  store, as one type of key-value stores, is applied in many practical systems since
  it could eliminate random writes and provide good read performance at the same time.
  However, the data residing in disk needs compaction operations from time to time,
  which takes a large amount of I/O resources. Since disk access speed is much slower
  than DRAM and most data resides in disks, the compaction operation will significantly
  influence the system performance. In this paper, we propose a grouped level structure,
  which divides each level in LSMT into multiple groups. Also, we propose a new compaction
  method for the grouped level structure to reduce the compaction I/O overhead. Our
  experiments show that the grouped level structure saves about 55% to 78% I/O resource
  of compaction, so it improves the write throughput by 69% to 284%, but only reduces
  the read throughput by 5% to 9%. It improves the overall throughput by 30% to 69%
  with read dominated workloads of 25% write operations and 75% read operations.
publication: '*2016 IEEE 22nd International Conference on Parallel and Distributed
  Systems (ICPADS)*'
doi: 10.1109/ICPADS.2016.0079
---
