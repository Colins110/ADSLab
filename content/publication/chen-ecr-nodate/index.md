---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'ECR: Eviction-cost-aware cache management policy for page-level flash-based
  SSDs'
subtitle: ''
summary: ''
authors:
- Hao Chen
- Yubiao Pan
- Cheng Li
- Yinlong Xu
tags:
- '"cache management"'
- '"flash memory"'
- '"SSD"'
categories: []
date: -01-01
lastmod: 2020-10-16T11:09:25+08:00
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
publishDate: '2020-10-16T03:09:25.205368Z'
publication_types:
- '2'
abstract: Cache management policy plays a key role in offering low latency access
  to flash-based SSDs. Most existing solutions including LRU and its successors only
  focus on improving the cache hit ratio, but rarely consider to reduce the waiting
  time of the eviction operation in the page-level mapping FTLs. As the workloads
  spreading across internal chips of modern flash-based SSDs are often highly imbalanced
  when workloads are write-intensive, the time cost of evicting a dirty page from
  cache varies in a wide range. In this paper, we propose a novel eviction-cost-aware
  cache management policy, called ECR, to minimize the eviction cost in write-dominant
  applications. ECR gives a higher probability to evict a page, which causes the shortest
  waiting time in the corresponding chip queue. To achieve this, we introduce a monitor
  module to keep track of states of all chip queues, and a multi-LRU list structure
  to accelerate the selection of a victim chip and a target page in cache to perform
  an eviction. Our experimental results show that ECR can significantly reduce the
  average response time by as much as 59.55% and 44.84% compared to LRU and GCaR-CFLRU,
  respectively, where GCaR-CFLRU is the combination of state-of-the-art algorithm
  GCaR and CFLRU.
publication: '*Concurrency and Computation: Practice and Experience*'
url_pdf: https://onlinelibrary.wiley.com/doi/abs/10.1002/cpe.5395
doi: 10.1002/cpe.5395
---
