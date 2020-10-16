---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Dynamic routing for network throughput maximization in software-defined networks
subtitle: ''
summary: ''
authors:
- Meitian Huang
- Weifa Liang
- Zichuan Xu
- Wenzheng Xu
- Song Guo
- Yinlong Xu
tags:
- '"Bandwidth"'
- '"bandwidth demand constraints"'
- '"computational complexity"'
- '"content-addressable storage"'
- '"dynamic routing"'
- '"Measurement"'
- '"network architecture"'
- '"next generation networks"'
- '"next-generation networking"'
- '"O(Kε log n)"'
- '"O(log n)"'
- '"optimisation"'
- '"Routing"'
- '"SDN"'
- '"software defined networking"'
- '"software-defined networks"'
- '"switch nodes"'
- '"Switches"'
- '"TCAM"'
- '"ternary content addressable memory"'
- '"Throughput"'
- '"Unicast"'
categories: []
date: '2016-04-01'
lastmod: 2020-10-16T11:09:18+08:00
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
publishDate: '2020-10-16T03:09:18.219236Z'
publication_types:
- '1'
abstract: Software-Defined Networking (SDN) has emerged as the paradigm of the next-generation
  networking through separating the data control plane from the data plane. The forwarding
  routing table at each of its switch nodes is usually implemented by expensive and
  power-hungry Ternary Content Addressable Memory (TCAM) that only has limited number
  of entries, and the bandwidth at each of its links is bounded too. Under this new
  network architecture, providing a quality service to users by admitting user requests
  to meet their resource demands is challenging, and very little attention has ever
  been paid in this regard. In this paper, we will study online unicast and multicast
  request admissions in SDNs with the aim to maximize the network throughput under
  both critical network resources and user bandwidth demand constraints, for which
  we first propose a novel model to characterize the usage costs of node and link
  resources. We then devise efficient online algorithms for unicast and multicast
  requests. We also analyze the competitive ratios of the proposed online algorithms,
  which are O(log n) and O(Kϵ log n) for unicasting and multicasting, respectively,
  where n is the network size, K is the maximum number of members in a multicast request,
  and ϵ is a constant with 0 textless; e ≤ 1. We finally evaluate the proposed algorithms
  empirically through simulations. The simulation results demonstrate that the proposed
  algorithms are very promising.
publication: '*IEEE INFOCOM 2016 - The 35th Annual IEEE International Conference on
  Computer Communications*'
doi: 10.1109/INFOCOM.2016.7524613
---
