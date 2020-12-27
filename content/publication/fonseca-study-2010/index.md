---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A study of the internal and external effects of concurrency bugs
subtitle: ''
summary: ''
authors:
- P. Fonseca
- Cheng Li
- V. Singhal
- R. Rodrigues
tags:
- '"parallel programming"'
- '"SQL"'
- '"Computer bugs"'
- '"concurrency bug"'
- '"Concurrent computing"'
- '"concurrent programming"'
- '"data structure"'
- '"database server"'
- '"error prone task"'
- '"Fault detection"'
- '"Interleaved codes"'
- '"Manufacturing processes"'
- '"multicore era"'
- '"multiprocessing programs"'
- '"MySQL"'
- '"Performance gain"'
- '"program debugging"'
- '"Programming profession"'
- '"Software performance"'
- '"Software systems"'
categories: []
date: '2010-06-01'
lastmod: 2020-12-27T11:32:01+08:00
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
publishDate: '2020-12-27T03:32:01.455197Z'
publication_types:
- '1'
abstract: Concurrent programming is increasingly important for achieving performance
  gains in the multi-core era, but it is also a difficult and error-prone task. Concurrency
  bugs are particularly difficult to avoid and diagnose, and therefore in order to
  improve methods for handling such bugs, we need a better understanding of their
  characteristics. In this paper we present a study of concurrency bugs in MySQL,
  a widely used database server. While previous studies of real-world concurrency
  bugs exist, they have centered their attention on the causes of these bugs. In this
  paper we provide a complementary focus on their effects, which is important for
  understanding how to detect or tolerate such bugs at run-time. Our study uncovered
  several interesting facts, such as the existence of a significant number of latent
  concurrency bugs, which silently corrupt data structures and are exposed to the
  user potentially much later. We also highlight several implications of our findings
  for the design of reliable concurrent systems.
publication: '*2010 IEEE/IFIP International Conference on Dependable Systems Networks
  (DSN)*'
doi: 10.1109/DSN.2010.5544315
---
