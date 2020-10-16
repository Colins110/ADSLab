---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Sampling online social networks via heterogeneous statistics
subtitle: ''
summary: ''
authors:
- Xin Wang
- Richard T. B. Ma
- Yinlong Xu
- Zhipeng Li
tags:
- '"asymptotic variance"'
- '"Benchmark testing"'
- '"Computers"'
- '"Conferences"'
- '"Estimation"'
- '"greedy algorithms"'
- '"greedy allocation"'
- '"heterogeneous statistics"'
- '"online social network"'
- '"OSN"'
- '"Resource management"'
- '"sampling methods"'
- '"Sampling methods"'
- '"sampling technique"'
- '"Social network services"'
- '"social networking (online)"'
categories: []
date: '2015-04-01'
lastmod: 2020-10-16T11:09:21+08:00
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
publishDate: '2020-10-16T03:09:21.148387Z'
publication_types:
- '1'
abstract: Most sampling techniques for online social networks (OSNs) are based on
  a particular sampling method on a single graph, which is referred to as a statistic.
  However, various realizing methods on different graphs could possibly be used in
  the same OSN, and they may lead to different sampling efficiencies, i.e., asymptotic
  variances. To utilize multiple statistics for accurate measurements, we formulate
  a mixture sampling problem, through which we construct a mixture unbiased estimator
  which minimizes the asymptotic variance. Given fixed sampling budgets for different
  statistics, we derive the optimal weights to combine the individual estimators;
  given a fixed total budget, we show that a greedy allocation towards the most efficient
  statistic is optimal. In practice, the sampling efficiencies of statistics can be
  quite different for various targets and are unknown before sampling. To solve this
  problem, we design a two-stage framework which adaptively spends a partial budget
  to test different statistics and allocates the remaining budget to the inferred
  best statistic. We show that our two-stage framework is a generalization of 1) randomly
  choosing a statistic and 2) evenly allocating the total budget among all available
  statistics, and our adaptive algorithm achieves higher efficiency than these benchmark
  strategies in theory and experiment.
publication: '*2015 IEEE Conference on Computer Communications (INFOCOM)*'
doi: 10.1109/INFOCOM.2015.7218649
---
