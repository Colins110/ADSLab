---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Modeling SSD RAID reliability under general settings
subtitle: ''
summary: ''
authors:
- Zhiyong Wu
- Yongkun Li
- Patrick P. C. Lee
- Yinlong Xu
tags:
- '"CTMC"'
- '"reliability"'
- '"SSD RAID"'
- '"transient analysis"'
categories: []
date: '2018-05-01'
lastmod: 2020-10-16T11:09:11+08:00
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
publishDate: '2020-10-16T03:09:10.604230Z'
publication_types:
- '1'
abstract: 'Solid-state drives (SSDs) are susceptible to the limited number of program/erase
  (P/E) cycles and uncorrectable flash errors, and hence achieving high reliability
  of SSD storage systems is a critical issue. RAID provides a viable option for enhancing
  system reliability by distributing redundancy across a number of SSDs. However,
  the flash error rate of an SSD increases with the number of P/E cycles, and this
  time-varying nature complicates the reliability analysis of SSD RAID. In addition,
  there remains very limited formal analysis that quantifies the reliability dynamics
  of an SSD RAID array under general settings. To this end, we propose a new continuous
  time Markov chain (CTMC) model to characterize the reliability dynamics of SSD RAID
  over time under two general settings: (1) fault tolerance against a general number
  of device failures and (2) non-uniform workload. We validate the correctness of
  our CTMC model via trace-driven simulations. Based on our model, we further analyze
  the impact of different RAID parameters on the reliability dynamics of an SSD RAID
  array.'
publication: '*Proceedings of the 15th ACM International Conference on Computing Frontiers*'
url_pdf: https://doi.org/10.1145/3203217.3203236
doi: 10.1145/3203217.3203236
---
