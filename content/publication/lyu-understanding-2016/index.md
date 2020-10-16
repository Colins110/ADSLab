---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Understanding the Sparse Vector Technique for Differential Privacy
subtitle: ''
summary: ''
authors:
- Min Lyu
- Dong Su
- Ninghui Li
tags:
- '"Computer Science - Cryptography and Security"'
categories: []
date: '2016-09-01'
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
publishDate: '2020-10-16T03:09:26.965540Z'
publication_types:
- '2'
abstract: The Sparse Vector Technique (SVT) is a fundamental technique for satisfying
  differential privacy and has the unique quality that one can output some query answers
  without apparently paying any privacy cost. SVT has been used in both the interactive
  setting, where one tries to answer a sequence of queries that are not known ahead
  of the time, and in the non-interactive setting, where all queries are known. Because
  of the potential savings on privacy budget, many variants for SVT have been proposed
  and employed in privacy-preserving data mining and publishing. However, most variants
  of SVT are actually not private. In this paper, we analyze these errors and identify
  the misunderstandings that likely contribute to them. We also propose a new version
  of SVT that provides better utility, and introduce an effective technique to improve
  the performance of SVT. These enhancements can be applied to improve utility in
  the interactive setting. Through both analytical and experimental comparisons, we
  show that, in the non-interactive setting (but not the interactive setting), the
  SVT technique is unnecessary, as it can be replaced by the Exponential Mechanism
  (EM) with better accuracy.
publication: '*arXiv:1603.01699 [cs]*'
url_pdf: http://arxiv.org/abs/1603.01699
---
