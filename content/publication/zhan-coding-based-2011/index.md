---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Coding-Based Data Broadcast Scheduling in On-Demand Broadcast
subtitle: ''
summary: ''
authors:
- C. Zhan
- V. C. S. Lee
- J. Wang
- Y. Xu
tags:
- '"Encoding"'
- '"Heuristic algorithms"'
- '"Servers"'
- '"network coding"'
- '"Network coding"'
- '"broadcast communication"'
- '"broadcast tick"'
- '"broadcasting"'
- '"clique"'
- '"coding-based data broadcast scheduling"'
- '"Data broadcast scheduling"'
- '"data scheduling algorithm"'
- '"Databases"'
- '"information dissemination"'
- '"network theory (graphs)"'
- '"on-demand broadcast"'
- '"packet encoding"'
- '"Scheduling algorithm"'
- '"scheduling algorithm representation"'
- '"weighted maximum clique problem"'
categories: []
date: '2011-11-01'
lastmod: 2020-12-27T11:32:03+08:00
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
publishDate: '2020-12-27T03:32:02.894628Z'
publication_types:
- '2'
abstract: According to data broadcast, we can satisfy multiple requests for the same
  data item in a broadcast tick. However, there is no significant breakthrough in
  performance improvement until recently that some studies proposed to use network
  coding in data broadcast. After broadcasting an encoded packet which encodes a number
  of data items, multiple clients can retrieve different requested data items in a
  broadcast tick. This not only utilizes bandwidth more efficiently, but also improves
  system performance. In this work, we propose a generalized encoding framework to
  incorporate network coding into data scheduling algorithms for on-demand broadcast.
  In the framework, data scheduling can be formulated as a weighted maximum clique
  problem in a graph where the weight of the clique is defined according to the performance
  objectives of the applications. Under the proposed framework, existing data scheduling
  algorithms for on-demand broadcast can be migrated into their corresponding coding
  versions while preserving their original criteria in scheduling data items. Our
  simulation results using a number of representative scheduling algorithms show that
  significant performance improvement can be achieved with coding.
publication: '*IEEE Transactions on Wireless Communications*'
doi: 10.1109/TWC.2011.092011.101652
---
