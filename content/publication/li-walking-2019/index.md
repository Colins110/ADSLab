---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Walking with Perception: Efficient Random Walk Sampling via Common Neighbor
  Awareness'
subtitle: ''
summary: ''
authors:
- Yongkun Li
- Zhiyong Wu
- Shuai Lin
- Hong Xie
- Min Lv
- Yinlong Xu
- John C.S. Lui
tags:
- '"bias analysis"'
- '"CNARW"'
- '"common neighbor aware random walk framework"'
- '"common neighbor awareness"'
- '"computational efficiency"'
- '"Computer science"'
- '"Convergence"'
- '"convergence rate"'
- '"Estimation"'
- '"Graph Analysis"'
- '"graph theory"'
- '"large-scale graph analysis tasks"'
- '"Legged locomotion"'
- '"Markov processes"'
- '"next-hop candidate nodes"'
- '"Probability distribution"'
- '"random processes"'
- '"Random Walk"'
- '"random walk sampling"'
- '"random walk sampling algorithms"'
- '"real-world network datasets"'
- '"sampling framework"'
- '"sampling methods"'
- '"social networking (online)"'
- '"Task analysis"'
- '"unbiased sampling schemes"'
categories: []
date: '2019-04-01'
lastmod: 2020-10-16T11:09:08+08:00
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
publishDate: '2020-10-16T03:09:07.916230Z'
publication_types:
- '1'
abstract: Random walk is widely applied to sample large-scale graphs due to its simplicity
  of implementation and solid theoretical foundations of bias analysis. However, its
  computational efficiency is heavily limited by the slow convergence rate (a.k.a.
  long burn-in period). To address this issue, we propose a common neighbor aware
  random walk framework called CNARW, which leverages weighted walking by differentiating
  the next-hop candidate nodes to speed up the convergence. Specifically, CNARW takes
  into consideration the common neighbors between previously visited nodes and next-hop
  candidate nodes in each walking step. Based on CNARW, we further develop two efficient
  \"unbiased sampling\" schemes. Experimental results on real-world network datasets
  show that our approach converges remarkably faster than the state-of-the-art random
  walk sampling algorithms. Furthermore, to achieve the same estimation accuracy,
  our approach reduces the query cost (a measure of sampling budget) significantly.
  Lastly, we also use two case studies to demonstrate the effectiveness of our sampling
  framework in solving large-scale graph analysis tasks.
publication: '*2019 IEEE 35th International Conference on Data Engineering (ICDE)*'
doi: 10.1109/ICDE.2019.00090
---
