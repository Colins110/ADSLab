---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Stochastic modeling and optimization of garbage collection algorithms in solid-state
  drive systems
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Patrick P. C. Lee
- John C. S. Lui
tags: []
categories: []
date: '2014-06-01'
lastmod: 2020-10-16T11:09:34+08:00
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
publishDate: '2020-10-16T03:09:33.666503Z'
publication_types:
- '2'
abstract: Markov chains and mean-field analysis are powerful tools and widely used
  for performance analysis in large-scale computer and communication systems. In this
  paper, we consider the application of Markov modeling and mean-field analysis to
  solid-state drives (SSDs). SSDs are now widely deployed in mobiles, desktops, and
  data centers due to their high I/O performance and low energy consumption. In particular,
  we focus on characterizing the performance–durability tradeoff of garbage collection
  (GC) algorithms in SSDs. Specifically, we first develop a stochastic Markov chain
  model to capture the I/O dynamics of large-scale SSDs, then adapt mean-field analysis
  to derive the asymptotic steady state, based on which we are able to easily analyze
  the performance–durability tradeoff of a large family of GC algorithms. We further
  prove the model convergence and generalize the model for all types of workload.
  Inspired by this model, we also propose a randomized greedy algorithm (RGA) which
  has a single tunable parameter to trade between performance and durability. Using
  trace-driven simulation on DiskSim with SSD add-ons, we demonstrate how RGA can
  be parameterized to realize the performance–durability tradeoff.
publication: '*Queueing Syst*'
url_pdf: https://doi.org/10.1007/s11134-014-9405-y
doi: 10.1007/s11134-014-9405-y
---
