---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Stochastic modeling of large-scale solid-state storage systems: analysis,
  design tradeoffs and optimization'
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Patrick P.C. Lee
- John C.S. Lui
tags:
- '"solid-state drives"'
- '"cleaning cost"'
- '"garbage collection"'
- '"mean field analysis"'
- '"stochastic modeling"'
- '"wear-leveling"'
categories: []
date: '2013-06-01'
lastmod: 2020-12-27T11:31:59+08:00
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
publishDate: '2020-12-27T03:31:59.791170Z'
publication_types:
- '1'
abstract: Solid state drives (SSDs) have seen wide deployment in mobiles, desktops,and
  data centers due to their high I/O performance and low energy consumption. As SSDs
  write data out-of-place, garbage collection (GC) is required to erase and reclaim
  space with invalid data. However, GC poses additional writes that hinder the I/O
  performance, while SSD blocks can only endure a finite number of erasures. Thus,
  there is a performance-durability tradeoff on the design space of GC. To characterize
  the optimal tradeoff, this paper formulates an analytical model that explores the
  full optimal design space of any GC algorithm. We first present a stochastic Markov
  chain model that captures the I/O dynamics of large-scale SSDs, and adapt the mean-field
  approach to derive the asymptotic steady-state performance. We further prove the
  model convergence and generalize the model for all types of workload. Inspired by
  this model, we propose a randomized greedy algorithm (RGA) that can operate along
  the optimal tradeoff curve with a tunable parameter. Using trace-driven simulation
  on DiskSim with SSD add-ons, we demonstrate how RGA can be parameterized to realize
  the performance-durability tradeoff.
publication: '*Proceedings of the ACM SIGMETRICS/international conference on Measurement
  and modeling of computer systems*'
url_pdf: https://doi.org/10.1145/2465529.2465546
doi: 10.1145/2465529.2465546
---
