---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Dual partitioning multicasting for high-performance on-chip networks
subtitle: ''
summary: ''
authors:
- Jianhua Li
- Liang Shi
- Chun Jason Xue
- Yinlong Xu
tags:
- '"Latency-aware"'
- '"Load-balance"'
- '"Multicast routing"'
- '"On-chip network"'
- '"Rectilinear Steiner tree"'
categories: []
date: '2014-01-01'
lastmod: 2020-10-16T11:09:32+08:00
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
publishDate: '2020-10-16T03:09:31.976500Z'
publication_types:
- '2'
abstract: As the number of cores integrated onto a single chip increases, power dissipation
  and network latency become ever-increasingly stringent. On-chip network provides
  an efficient and scalable interconnection paradigm for chip multiprocessors (CMPs),
  wherein one-to-many (multicast) communication is universal for such platforms. Without
  efficient multicasting support, traditional unicasting on-chip networks will be
  low efficiency in tackling such multicast communication. In this paper, we propose
  Dual Partitioning Multicasting (DPM) to reduce packet latency and balance network
  resource utilization. Specifically, DPM scheme adaptively makes routing decisions
  based on the network load-balance level as well as the link sharing patterns characterized
  by the distribution of the multicasting destinations. Extensive experimental results
  for synthetic traffic as well as real applications show that compared with the recently
  proposed RPM scheme, DPM significantly reduces the average packet latency and mitigates
  the network power consumption. More importantly, DPM is highly scalable for future
  on-chip networks with heavy traffic load and varieties of traffic patterns.
publication: '*Journal of Parallel and Distributed Computing*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0743731513001287
doi: 10.1016/j.jpdc.2013.07.002
---
