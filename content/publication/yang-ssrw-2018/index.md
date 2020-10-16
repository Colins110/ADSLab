---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'SSRW: A Scalable Algorithm for Estimating Graphlet Statistics Based on Random
  Walk'
subtitle: ''
summary: ''
authors:
- Chen Yang
- Min Lyu
- Yongkun Li
- Qianqian Zhao
- Yinlong Xu
tags:
- '"Exact Count"'
- '"Graphlet Count"'
- '"Graphs Let"'
- '"Subgraph Sampling"'
- '"Super Graph"'
categories: []
date: '2018-01-01'
lastmod: 2020-10-16T11:09:10+08:00
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
publishDate: '2020-10-16T03:09:10.254228Z'
publication_types:
- '1'
abstract: Mining graphlet statistics is very meaningful due to its wide applications
  in social networks, bioinformatics and information security, etc. However, it is
  a big challenge to exactly count graphlet statistics as the number of subgraphs
  exponentially increases with the graph size, so sampling algorithms are widely used
  to estimate graphlet statistics within reasonable time. However, existing sampling
  algorithms are not scalable for large graphlets, e.g., they may get stuck when estimating
  graphlets with more than five nodes. To address this issue, we propose a highly
  scalable algorithm, Scalable subgraph Sampling via Random Walk (SSRW), for graphlet
  counts and concentrations. SSRW samples graphlets by generating new nodes from the
  neighbors of previously visited nodes instead of fixed ones. Thanks to this flexibility,
  we can generate any k-graphlets in a unified way and estimate statistics of k-graphlet
  efficiently even for large k. Our extensive experiments on estimating counts and
  concentrations of 4,5,6,74,5,6,74,5,6,7-graphlets show that SSRW algorithm is scalable,
  accurate and fast.
publication: '*Database Systems for Advanced Applications*'
doi: 10.1007/978-3-319-91452-7_18
---
