---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Enabling Efficient Updates in KV Storage via Hashing: Design and Performance
  Evaluation'
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Helen H. W. Chan
- Patrick P. C. Lee
- Yinlong Xu
tags:
- '"Hashing"'
- '"Key-value storage"'
- '"LSM-tree"'
categories: []
date: '2019-08-01'
lastmod: 2020-10-16T11:09:23+08:00
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
publishDate: '2020-10-16T03:09:23.376368Z'
publication_types:
- '2'
abstract: Persistent key-value (KV) stores mostly build on the Log-Structured Merge
  (LSM) tree for high write performance, yet the LSM-tree suffers from the inherently
  high I/O amplification. KV separation mitigates I/O amplification by storing only
  keys in the LSM-tree and values in separate storage. However, the current KV separation
  design remains inefficient under update-intensive workloads due to its high garbage
  collection (GC) overhead in value storage. We propose HashKV, which aims for high
  update performance atop KV separation under update-intensive workloads. HashKV uses
  hash-based data grouping, which deterministically maps values to storage space to
  make both updates and GC efficient. We further relax the restriction of such deterministic
  mappings via simple but useful design extensions. We extensively evaluate various
  design aspects of HashKV. We show that HashKV achieves 4.6× update throughput and
  53.4% less write traffic compared to the current KV separation design. In addition,
  we demonstrate that we can integrate the design of HashKV with state-of-the-art
  KV stores and improve their respective performance.
publication: '*ACM Trans. Storage*'
url_pdf: https://doi.org/10.1145/3340287
doi: 10.1145/3340287
---
