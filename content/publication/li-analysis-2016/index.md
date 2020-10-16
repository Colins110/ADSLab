---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Analysis of Reliability Dynamics of SSD RAID
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Patrick P.C. Lee
- John C.S. Lui
tags:
- '"Aging"'
- '"Arrays"'
- '"Ash"'
- '"bit error rate"'
- '"continuous time Markov chain model"'
- '"CTMC"'
- '"data centers"'
- '"desktops"'
- '"Error analysis"'
- '"error statistics"'
- '"flash memories"'
- '"Markov processes"'
- '"numerical analysis"'
- '"Numerical models"'
- '"RAID"'
- '"reliability"'
- '"Reliability"'
- '"reliability dynamics"'
- '"solid-state drives"'
- '"Solid-state drives"'
- '"SSD RAID"'
- '"trace-driven simulation"'
- '"transient analysis"'
- '"Transient analysis"'
categories: []
date: '2016-04-01'
lastmod: 2020-10-16T11:09:28+08:00
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
publishDate: '2020-10-16T03:09:28.523500Z'
publication_types:
- '2'
abstract: Solid-state drives (SSDs) have been widely deployed in desktops and data
  centers. However, SSDs suffer from bit errors, and the bit error rate is time dependent
  since it increases as an SSD wears down. Traditional storage systems mainly use
  parity-based RAID to provide reliability guarantees by striping redundancy across
  multiple devices, but the effectiveness of traditional RAID schemes in SSDs remains
  debatable. In particular, an open problem is how different parity distributions
  over multiple devices influence the reliability of an SSD RAID array. That is, should
  we evenly distribute patsaverties as suggested by conventional wisdom, or unevenly
  distribute parties as recently proposed for SSD RAID? To address this fundamental
  problem, we propose the first analytical model to quantify the reliability dynamics
  of an SSD RAID array as it ages. Specifically, we develop a “non-homogeneous” continuous
  time Markov chain model, and derive the transient reliability solution. We validate
  our model via trace-driven simulation and conduct numerical analysis to analyze
  the reliability dynamics of SSD RAID arrays subject to different parity distributions,
  error rates, and SSD array configurations. Our model enables system practitioners
  to decide the appropriate parity distribution based on their reliability requirements.
publication: '*IEEE Transactions on Computers*'
doi: 10.1109/TC.2014.2349505
---
