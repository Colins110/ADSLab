---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Geo-Replication: Fast If Possible, Consistent If Necessary'
subtitle: ''
summary: ''
authors:
- Valter Balegas
- Cheng Li
- Mahsa Najafzadeh
- Daniel Porto
- Allen Clement
- Sérgio Duarte
- Carla Ferreira
- Johannes Gehrke
- João Leitão
- Nuno Preguiça
- Rodrigo Rodrigues
- Marc Shapiro
- Viktor Vafeiadis
tags: []
categories: []
date: '2016-03-01'
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
publishDate: '2020-10-16T03:09:29.017499Z'
publication_types:
- '2'
abstract: Geo-replicated storage systems are at the core of current Internet services.
  Unfortunately, there exists a fundamental tension between consistency and performance
  for offering scalable geo-replication. Weakening consistency semantics leads to
  less coordination and consequently a good user experience, but it may introduce
  anomalies such as state divergence and invariant violation. In contrast, maintaining
  stronger consistency precludes anomalies but requires more coordination. This paper
  discusses two main contributions to address this tension. First, RedBlue Consistency
  enables blue operations to be fast (and weakly consistent) while the remaining red
  operations are strongly consistent (and slow). We identify sufficient conditions
  for determining when operations can be blue or must be red. Second, Explicit Consistency
  further increases the space of operations that can be fast by restricting the concurrent
  execution of only the operations that can break application-defined invariants.
  We further show how to allow operations to complete locally in the common case,
  by relying on a reservation system that moves coordination off the critical path
  of operation execution.
publication: '*Bulletin of the Technical Committee on Data Engineering*'
url_pdf: https://hal.inria.fr/hal-01350652
---
