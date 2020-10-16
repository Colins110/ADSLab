---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Thread Progress Aware Coherence Adaption for Hybrid Cache Coherence Protocols
subtitle: ''
summary: ''
authors:
- Jianhua Li
- Liang Shi
- Qing'an Li
- Chun Jason Xue
- Yinlong Xu
tags:
- '"Cache coherence"'
- '"cache coherence policy"'
- '"cache storage"'
- '"chip multiprocessor system"'
- '"chip multiprocessor systems"'
- '"CMP"'
- '"CMP systems"'
- '"Coherence"'
- '"coherence protocol"'
- '"energy conservation"'
- '"energy consumption reduction"'
- '"energy efficiency"'
- '"Estimation"'
- '"hybrid cache coherence protocols"'
- '"Instruction sets"'
- '"laggard threads"'
- '"leader threads"'
- '"memory system statistics"'
- '"Message systems"'
- '"multiprocessing systems"'
- '"on-chip cache"'
- '"parallel application"'
- '"Protocols"'
- '"shared resources"'
- '"synchronisation"'
- '"synchronization primitives"'
- '"System-on-chip"'
- '"TEACA"'
- '"thread progress aware coherence adaption"'
- '"thread progress information"'
categories: []
date: '2014-10-01'
lastmod: 2020-10-16T11:09:32+08:00
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
publishDate: '2020-10-16T03:09:32.378501Z'
publication_types:
- '2'
abstract: For chip multiprocessor systems (CMPs), the interference on shared resources
  such as on-chip caches typically leads to unbalanced progress among threads. Because
  of the inherent synchronization primitives, such as barriers and locks, cores running
  fast threads have to waste precious cycles to wait for cores with slow progress,
  which leads to performance and energy inefficiency. For the purpose of improving
  performance and reducing energy consumption, this paper proposes to adapt the cache
  coherence policy for threads according to their delay-tolerant levels. Specifically,
  this paper proposes Thread progrEss Aware Coherence Adaption (TEACA) which utilizes
  the thread progress information as hints for coherence adaption. TEACA dynamically
  utilize the memory system statistics to estimate the progress of threads. Based
  on the estimated thread progress information, TEACA categorizes threads into leader
  threads and laggard threads. The thread categorization decisions are then leveraged
  for efficient coherence adaption on CMP systems supporting hybrid coherence protocols.
  Experimental results show that, on a 64-core CMP system, TEACA outperforms directory
  protocol in application execution time and a recently proposed hybrid protocol in
  both application execution time and energy dissipation.
publication: '*IEEE Transactions on Parallel and Distributed Systems*'
doi: 10.1109/TPDS.2013.228
---
