---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Low-energy volatile STT-RAM cache design using cache-coherence-enabled adaptive
  refresh
subtitle: ''
summary: ''
authors:
- Jianhua Li
- Liang Shi
- Qingan Li
- Chun Jason Xue
- Yiran Chen
- Yinlong Xu
- Wei Wang
tags:
- '"cache coherence"'
- '"embedded DRAM"'
- '"energy efficiency"'
- '"nonvolatile memory"'
- '"refresh"'
- '"Spin-torque transfer RAM"'
categories: []
date: '2013-12-01'
lastmod: 2020-10-16T11:09:30+08:00
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
publishDate: '2020-10-16T03:09:30.245499Z'
publication_types:
- '2'
abstract: Spin-Torque Transfer RAM (STT-RAM) is a promising candidate for SRAM replacement
  because of its excellent features, such as fast read access, high density, low leakage
  power, and CMOS technology compatibility. However, wide adoption of STT-RAM as cache
  memories is impeded by its long write latency and high write power. Recent work
  proposed improving the write performance through relaxing the retention time of
  STT-RAM cells. The resultant volatile STT-RAM needs to be periodically refreshed
  to prevent data loss. When volatile STT-RAM is applied as the last-level cache (LLC)
  in chip multiprocessor (CMP) systems, frequent refresh operations could dissipate
  significant extra energy. In addition, refresh operations could severely conflict
  with normal read/write operations to degrade overall system performance. Therefore,
  minimizing the performance impact caused by refresh operations is crucial for the
  adoption of volatile STT-RAM. In this article, we propose Cache-Coherence-Enabled
  Adaptive Refresh (CCear) to minimize the number of refresh operations for volatile
  STT-RAM, adopted as the LLC for CMP systems. Specifically, CCear interacts with
  cache coherence protocol and cache management policy to minimize the number of refresh
  operations on volatile STT-RAM caches. Full-system simulation results show that
  CCear performs close to an ideal refresh policy with low overhead. Compared with
  state-of-the-art refresh policies, CCear simultaneously improves the system performance
  and reduces the energy consumption. Moreover, the performance of CCear could be
  further enhanced using small filter caches to accommodate the not-refreshed private
  STT-RAM blocks.
publication: '*ACM Trans. Des. Autom. Electron. Syst.*'
url_pdf: https://doi.org/10.1145/2534393
doi: 10.1145/2534393
---
