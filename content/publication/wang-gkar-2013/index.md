---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'GKAR: A Novel Geographic K-anycast Routing for Wireless Sensor Networks'
subtitle: ''
summary: ''
authors:
- X. Wang
- J. Wang
- K. Lu
- Y. Xu
tags:
- '"Algorithm design and analysis"'
- '"Servers"'
- '"Routing protocols"'
- '"distributed storage system"'
- '"Energy consumption"'
- '"Routing"'
- '"$(K)$-anycast"'
- '"communication overhead"'
- '"distributed access"'
- '"distributed geographic K-anycast routing protocol"'
- '"geographic routing"'
- '"GKAP scheme"'
- '"GKAR protocol"'
- '"intermediate node"'
- '"iterative approach"'
- '"K-delivery"'
- '"multisink scheme"'
- '"query data"'
- '"routing protocols"'
- '"wireless sensor network"'
- '"wireless sensor networks"'
- '"Wireless sensor networks"'
- '"WSN"'
categories: []
date: '2013-05-01'
lastmod: 2020-12-27T11:32:04+08:00
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
publishDate: '2020-12-27T03:32:03.938767Z'
publication_types:
- '2'
abstract: To efficiently archive and query data in wireless sensor networks (WSNs),
  distributed storage systems, and multisink schemes have been proposed recently.
  However, such distributed access cannot be fully supported and exploited by existing
  routing protocols in a large-scale WSN. In this paper, we will address this challenging
  issue and propose a distributed geographic K-anycast routing (GKAR) protocol for
  WSNs, which can efficiently route data from a source sensor to any K destinations
  (e.g., storage nodes or sinks). To guarantee K-delivery, an iterative approach is
  adopted in GKAR where in each round, GKAR will determine not only the next hops
  at each node, but also a set of potential destinations for every next hop node to
  reach. Efficient algorithms are designed to determine the selection of the next
  hops and destination set division at each intermediate node. We analyze the complexity
  of GKAR in each round and we also theoretically analyze the expected number of rounds
  required to guarantee K-delivery. Simulation results demonstrate the superiority
  of the GKAP scheme in reducing the total duration and the communication overhead
  for finding K destinations, by comparing with the existing schemes, e.g., K 1-anycast
  [10].
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2012.143
---
