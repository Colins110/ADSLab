---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Stochastic Analysis on RAID Reliability for Solid-State Drives
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Patrick P.C. Lee
- John C.S. Lui
tags:
- '"Aging"'
- '"array configurations"'
- '"Arrays"'
- '"bit error rate"'
- '"CTMC"'
- '"data centers"'
- '"desktops"'
- '"disc drives"'
- '"Error analysis"'
- '"Markov processes"'
- '"nonhomogeneous continuous time Markov chain model"'
- '"numerical analysis"'
- '"Numerical models"'
- '"parity distribution"'
- '"RAID"'
- '"redundancy"'
- '"Reliability"'
- '"reliability requirements"'
- '"solid-state drives"'
- '"Solid-state Drives"'
- '"SSD RAID array reliability dynamics"'
- '"stochastic analysis"'
- '"trace-driven simulation"'
- '"Transient analysis"'
- '"Transient Analysis"'
- '"transient reliability solution"'
categories: []
date: '2013-09-01'
lastmod: 2020-10-16T11:09:19+08:00
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
publishDate: '2020-10-16T03:09:19.250370Z'
publication_types:
- '1'
abstract: Solid-state drives (SSDs) have been widely deployed in desktops and data
  centers. However, SSDs suffer from bit errors, and the bit error rate is time dependent
  since it increases as an SSD wears down. Traditional storage systems mainly use
  parity-based RAID to provide reliability guarantees by striping redundancy across
  multiple devices, but the effectiveness of RAID in SSDs remains debatable as parity
  updates aggravate the wearing and bit error rates of SSDs. In particular, an open
  problem is that how different parity distributions over multiple devices, such as
  the even distribution suggested by conventional wisdom, or uneven distributions
  proposed in recent RAID schemes for SSDs, may influence the reliability of an SSD
  RAID array. To address this fundamental problem, we propose the first analytical
  model to quantify the reliability dynamics of an SSD RAID array. Specifically, we
  develop a \"non-homogeneous\" continuous time Markov chain model, and derive the
  transient reliability solution. We validate our model via trace-driven simulations
  and conduct numerical analysis to provide insights into the reliability dynamics
  of SSD RAID arrays under different parity distributions and subject to different
  bit error rates and array configurations. Designers can use our model to decide
  the appropriate parity distribution based on their reliability requirements.
publication: '*2013 IEEE 32nd International Symposium on Reliable Distributed Systems*'
doi: 10.1109/SRDS.2013.16
---
