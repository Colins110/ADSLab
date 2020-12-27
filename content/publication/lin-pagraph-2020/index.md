---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'PaGraph: Scaling GNN training on large graphs via computation-aware caching'
subtitle: ''
summary: ''
authors:
- Zhiqi Lin
- Cheng Li
- Youshan Miao
- Yunxin Liu
- Yinlong Xu
tags: []
categories: []
date: '2020-10-01'
lastmod: 2020-12-27T11:31:59+08:00
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
publishDate: '2020-12-27T03:31:59.360721Z'
publication_types:
- '1'
abstract: Emerging graph neural networks (GNNs) have extended the successes of deep
  learning techniques against datasets like images and texts to more complex graph-structured
  data. By leveraging GPU accelerators, existing frameworks combine both mini-batch
  and sampling for effective and efficient model training on large graphs. However,
  this setup faces a scalability issue since loading rich vertices features from CPU
  to GPU through a limited bandwidth link usually dominates the training cycle. In
  this paper, we propose PaGraph, a system that supports general and efficient sampling-based
  GNN training on single-server with multi-GPU. PaGraph significantly reduces the
  data loading time by exploiting available GPU resources to keep frequently accessed
  graph data with a cache. It also embodies a lightweight yet effective caching policy
  that takes into account graph structural information and data access patterns of
  sampling-based GNN training simultaneously. Furthermore, to scale out on multiple
  GPUs, PaGraph develops a fast GNN-computation-aware partition algorithm to avoid
  cross-partition access during data parallel training and achieves better cache efficiency.
  Evaluations on two representative GNN models, GCN and GraphSAGE, show that PaGraph
  achieves up to 96.8% data loading time reductions and up to 4.8× performance speedup
  over the state-of-the-art baselines. Together with preprocessing optimization, PaGraph
  further delivers up to 16.0× end-to-end speedup.
publication: '*Proceedings of the 11th ACM Symposium on Cloud Computing*'
url_pdf: https://dl.acm.org/doi/10.1145/3419111.3421281
doi: 10.1145/3419111.3421281
---
