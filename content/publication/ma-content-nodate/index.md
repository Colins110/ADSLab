---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A Content Distribution System based on Sparse Linear Network Coding
subtitle: ''
summary: ''
authors:
- Guanjun Ma
- Yinlong Xu
- Minghong Lin
- Ying Xuan
tags: []
categories: []
date: -01-01
lastmod: 2020-12-27T11:32:00+08:00
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
publishDate: '2020-12-27T03:32:00.411939Z'
publication_types:
- '5'
abstract: Abstract — With network coding, intermediate nodes between source and destination
  node(s) encode the incoming packets into new ones and forward them to their outgoing
  links. The original content is decoded at the destination node(s). Recent theoretical
  results show that network coding is beneficial for peer-to-peer(P2P) content distribution.
  To evaluate the benefit of network coding, we implement a P2P content distribution
  system based on the sparse linear network coding method. In our system, we use the
  Chord protocol to construct the system topology. We determine the proper encoding
  density so as to reach a high probability of generating independent encoded blocks,
  and to reduce the computational complexity of encoding packets at each peer. To
  improve the system performance, we use the encoding interval to reduce the probability
  of transmitting linear dependent packets and dependency test to avoid accepting
  linear dependent packets possibly from cyclic topology. Lastly, we carry out extensive
  experiments to show in terms of average downloading time at peers, total distribution
  time and system throughput, the system with network coding slightly outperforms
  a BitTorrent-like non-coding system using the local-rarest-first chunk selection
  policy. I.
publication: ''
---
