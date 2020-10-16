---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: I/O-Efficient Scaling Schemes for Distributed Storage Systems with CRS Codes
subtitle: ''
summary: ''
authors:
- Si Wu
- Yinlong Xu
- Yongkun Li
- Zhijia Yang
tags:
- '"Algorithm design and analysis"'
- '"cauchy reed-solomon codes"'
- '"Cauchy Reed-Solomon codes"'
- '"CRS codes"'
- '"data migration"'
- '"data migration policy"'
- '"Data models"'
- '"Distributed databases"'
- '"distributed storage systems"'
- '"Encoding"'
- '"encoding matrix"'
- '"fault-protection"'
- '"I/O overhead minimization"'
- '"I/O-efficient scaling schemes"'
- '"Layout"'
- '"matrix algebra"'
- '"maximum distance separable property"'
- '"MDS property"'
- '"minimal data movement"'
- '"multiple simultaneous node failures"'
- '"optimisation"'
- '"Optimization"'
- '"optimization model"'
- '"post-scaling encoding matrix"'
- '"Reed-Solomon codes"'
- '"Scaling"'
- '"software fault tolerance"'
- '"storage management"'
- '"system scaling scheme"'
- '"three-phase optimization scaling scheme"'
- '"uniform data distribution"'
categories: []
date: '2016-09-01'
lastmod: 2020-10-16T11:09:29+08:00
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
publishDate: '2020-10-16T03:09:29.400502Z'
publication_types:
- '2'
abstract: System scaling becomes essential and indispensable for distributed storage
  systems due to the explosive growth of data volume. Considering that fault-protection
  is a necessity in large-scale distributed storage systems, and Cauchy Reed-Solomon
  (CRS) codes are widely deployed to tolerate multiple simultaneous node failures,
  this paper studies the scaling problem of distributed storage systems with CRS codes.
  In particular, we formulate the scaling problem with an optimization model in which
  both the post-scaling encoding matrix and the data migration policy are assumed
  to be unknown in advance. To minimize the I/O overhead, we propose a three-phase
  optimization scaling scheme for CRS codes. Specifically, we first derive the optimal
  post-scaling encoding matrix under a given data migration policy, then optimize
  the data migration process using the selected post-scaling encoding matrix, and
  finally exploit the Maximum Distance Separable (MDS) property to further optimize
  the designed data migration process. Our scaling scheme requires minimal data movement
  while achieving uniform data distribution. Moreover, it requires to read fewer data
  blocks than conventional minimum data migration schemes, but still guarantees the
  minimum amount of migrated data. To validate the efficiency of our scheme, we implement
  it atop a networked file system. Extensive experiments show that our scaling scheme
  uses less scaling time than the basic scheme.
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2015.2505722
---
