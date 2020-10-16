---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Publishing Graph Degree Distribution with Node Differential Privacy
subtitle: ''
summary: ''
authors:
- Wei-Yen Day
- Ninghui Li
- Min Lyu
tags:
- '"degree distribution"'
- '"differential privacy"'
- '"private graph publishing"'
categories: []
date: '2016-06-01'
lastmod: 2020-10-16T11:09:14+08:00
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
publishDate: '2020-10-16T03:09:14.561230Z'
publication_types:
- '1'
abstract: Graph data publishing under node-differential privacy (node-DP) is challenging
  due to the huge sensitivity of queries. However, since a node in graph data oftentimes
  represents a person, node-DP is necessary to achieve personal data protection. In
  this paper, we investigate the problem of publishing the degree distribution of
  a graph under node-DP by exploring the projection approach to reduce the sensitivity.
  We propose two approaches based on aggregation and cumulative histogram to publish
  the degree distribution. The experiments demonstrate that our approaches greatly
  reduce the error of approximating the true degree distribution and have significant
  improvement over existing works. We also present the introspective analysis for
  understanding the factors of publishing the degree distribution with node-DP.
publication: '*Proceedings of the 2016 International Conference on Management of Data*'
url_pdf: https://doi.org/10.1145/2882903.2926745
doi: 10.1145/2882903.2926745
---
