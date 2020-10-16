---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Explicit Data Correlations-Directed Metadata Prefetching Method in Distributed
  File Systems
subtitle: ''
summary: ''
authors:
- Youxu Chen
- Cheng Li
- Min Lv
- Xinyang Shao
- Yongkun Li
- Yinlong Xu
tags:
- '"access correlations"'
- '"cache storage"'
- '"data correlations"'
- '"Data mining"'
- '"Data processing"'
- '"data-correlated files"'
- '"DFS"'
- '"distributed databases"'
- '"Distributed file system"'
- '"distributed file systems"'
- '"Distributed management"'
- '"explicit data correlations-directed metadata prefetching method"'
- '"feedback"'
- '"file accesses"'
- '"file metadata"'
- '"File systems"'
- '"meta data"'
- '"Metadata"'
- '"metadata operations"'
- '"metadata performance"'
- '"modern storage systems"'
- '"pattern matching"'
- '"prefetching"'
- '"Prefetching"'
- '"Servers"'
- '"SMeta"'
- '"storage management"'
- '"target file"'
categories: []
date: '2019-12-01'
lastmod: 2020-10-16T11:09:24+08:00
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
publishDate: '2020-10-16T03:09:24.411368Z'
publication_types:
- '2'
abstract: 'Metadata performance in distributed file systems (DFS) is critical, due
  to the following trends: (a) the growing size of modern storage systems is expected
  to exceed billions of files and most files are small; (b) over half of the file
  accesses are metadata operations. In this work, we present SMeta, a metadata prefetching
  method that is seamlessly integrated into DFS for easy-of-use and significantly
  scales the metadata performance. Previous prefetching proposals primarily focus
  on mining groups of files that tend to be accessed together from the access history.
  Nevertheless, our study discovered that these solutions likely miss a huge number
  of correlated files whose co-occurrence frequency is not high enough. Unlike access
  correlations, we take a novel and completely different approach to explore explicit
  data correlations by understanding the reference relationships between files encoded
  in some forms of hyperlinks, which naturally exist in many applications. To embrace
  this new concept, SMeta explores correlations upon files are written via a light-weight
  pattern matching algorithm, stores correlations in the reserved extended attributes
  of file metadata to avoid changes in DFS APIs, and collapses multiple I/O rounds
  for accessing metadata of the target file and its data-correlated files into one
  round. A cost-efficient adaptive feedback mechanism is introduced to improve prefetching
  accuracy. We implemented SMeta atop of Ceph and evaluated it using synthetic and
  real system workloads. Compared to baselines, SMeta provides better metadata performance
  in terms of latency, throughput and scalability.'
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2019.2921760
---
