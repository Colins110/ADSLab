---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Measuring and Maximizing Influence via Random Walk in Social Activity Networks
subtitle: ''
summary: ''
authors:
- Pengpeng Zhao
- Yongkun Li
- Hong Xie
- Zhiyong Wu
- Yinlong Xu
- John C. S. Lui
tags:
- '"Influence maximization"'
- '"OSN"'
- '"Random walk"'
categories: []
date: '2017-01-01'
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
publishDate: '2020-10-16T03:09:14.177233Z'
publication_types:
- '1'
abstract: With the popularity of OSNs, finding a set of most influential users (or
  nodes) so as to trigger the largest influence cascade is of significance. For example,
  companies may take advantage of the “word-of-mouth” effect to trigger a large cascade
  of purchases by offering free samples/discounts to those most influential users.
  This task is usually modeled as an influence maximization problem, and it has been
  widely studied in the past decade. However, considering that users in OSNs may participate
  in various kinds of online activities, e.g., giving ratings to products, joining
  discussion groups, etc., influence diffusion through online activities becomes even
  more significant.In this paper, we study the impact of online activities by formulating
  the influence maximization problem for social-activity networks (SANs) containing
  both users and online activities. To address the computation challenge, we define
  an influence centrality via random walks to measure influence, then use the Monte
  Carlo framework to efficiently estimate the centrality in SANs. Furthermore, we
  develop a greedy-based algorithm with two novel optimization techniques to find
  the most influential users. By conducting extensive experiments with real-world
  datasets, we show our approach is more efficient than the state-of-the-art algorithm
  IMM [17] when we needs to handle large amount of online activities.
publication: '*Database Systems for Advanced Applications*'
doi: 10.1007/978-3-319-55699-4_20
---
