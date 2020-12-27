---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'HAMS: High Availability for Distributed Machine Learning Service Graphs'
subtitle: ''
summary: ''
authors:
- S. Zhao
- X. Chen
- C. Wang
- F. Li
- Q. Ji
- H. Cui
- C. Li
- S. Wang
tags:
- '"Backup"'
- '"Computational modeling"'
- '"Data Center"'
- '"Deep Learning"'
- '"Determinism"'
- '"Distributed System"'
- '"Fault Tolerance"'
- '"Fault tolerant systems"'
- '"GPU"'
- '"Graphics processing units"'
- '"High Availability"'
- '"Inference"'
- '"Inference algorithms"'
- '"Machine Learning"'
- '"Microservice"'
- '"Nondeterminism"'
- '"Prediction"'
- '"Predictive models"'
- '"Replication"'
- '"SMR"'
- '"System"'
- '"Tensile stress"'
- '"Training"'
categories: []
date: '2020-06-01'
lastmod: 2020-12-27T11:31:58+08:00
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
publishDate: '2020-12-27T03:31:58.552523Z'
publication_types:
- '1'
abstract: "Mission-critical services often deploy multiple Machine Learning (ML) models\
  \ in a distributed graph manner, where each model can be deployed on a distinct\
  \ physical host. Practical fault tolerance for such ML service graphs should meet\
  \ three crucial requirements: high availability (fast failover), low normal case\
  \ performance overhead, and global consistency under non-determinism (e.g., threads\
  \ in a GPU can do floating point additions in random order). Unfortunately, despite\
  \ much effort, existing fault tolerance systems, including those taking the primary-backup\
  \ approach or the checkpoint-replay approach, cannot meet all these three requirements.\
  \ To tackle this problem, we present HAMS, which starts from the primary-backup\
  \ approach to replicate each stateful ML model, and we leverage the causal logging\
  \ technique from the checkpoint-replay approach to eliminate the notorious stop-and-buffer\
  \ delay in the primary-backup approach. Extensive evaluation on 25 ML models and\
  \ six ML services shows that: (1) in normal case, HAMS achieved 0.5%-3.7% overhead\
  \ on latency compared with bare metal; (2) HAMS took 116.12ms-254.19ms to recover\
  \ one stateful model in all services, 155.1X-1067.9X faster than a relevant system\
  \ Lineage Stash (LS); and (3) HAMS recovered these services with global consistency\
  \ even when the GPU non-determinism exists, not supported by LS. HAMS's code is\
  \ released ongithub.com/hku-systems/hams."
publication: '*2020 50th Annual IEEE/IFIP International Conference on Dependable Systems
  and Networks (DSN)*'
doi: 10.1109/DSN48063.2020.00036
---
