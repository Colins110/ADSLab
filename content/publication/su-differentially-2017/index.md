---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Differentially Private K-Means Clustering and a Hybrid Approach to Private
  Optimization
subtitle: ''
summary: ''
authors:
- Dong Su
- Jianneng Cao
- Ninghui Li
- Elisa Bertino
- Min Lyu
- Hongxia Jin
tags:
- '"Differential privacy"'
- '"k-means clustering"'
- '"private data publishing"'
categories: []
date: '2017-10-01'
lastmod: 2020-10-16T11:09:27+08:00
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
publishDate: '2020-10-16T03:09:27.328503Z'
publication_types:
- '2'
abstract: k-means clustering is a widely used clustering analysis technique in machine
  learning. In this article, we study the problem of differentially private k-means
  clustering. Several state-of-the-art methods follow the single-workload approach,
  which adapts an existing machine-learning algorithm by making each step private.
  However, most of them do not have satisfactory empirical performance. In this work,
  we develop techniques to analyze the empirical error behaviors of one of the state-of-the-art
  single-workload approaches, DPLloyd, which is a differentially private version of
  the Lloyd algorithm for ktextgreater-means clustering. Based on the analysis, we
  propose an improvement of DPLloyd. We also propose a new algorithm for k-means clustering
  from the perspective of the noninteractive approach, which publishes a synopsis
  of the input dataset and then runs k-means on synthetic data generated from the
  synopsis. We denote this approach by EUGkM. After analyzing the empirical error
  behaviors of EUGkM, we further propose a hybrid approach that combines our DPLloyd
  improvement and EUGkM. Results from extensive and systematic experiments support
  our analysis and demonstrate the effectiveness of the DPLloyd improvement, EUGkM,
  and the hybrid approach.
publication: '*ACM Trans. Priv. Secur.*'
url_pdf: https://doi.org/10.1145/3133201
doi: 10.1145/3133201
---
