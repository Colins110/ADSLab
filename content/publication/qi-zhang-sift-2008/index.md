---
# Documentation: https://wowchemy.com/docs/managing-content/

title: SIFT implementation and optimization for multi-core systems
subtitle: ''
summary: ''
authors:
- Qi Zhang
- Yurong Chen
- Yimin Zhang
- Yinlong Xu
tags:
- '"Feature extraction"'
- '"Scalability"'
- '"32-core chip multiprocessor"'
- '"Acceleration"'
- '"Analytical models"'
- '"computer vision"'
- '"Computer vision"'
- '"Face recognition"'
- '"feature extraction"'
- '"image matching"'
- '"Large-scale systems"'
- '"memory performance analysis"'
- '"microprocessor chips"'
- '"multi-core systems"'
- '"Multicore processing"'
- '"Object detection"'
- '"Performance analysis"'
- '"scale invariant feature transform"'
- '"SIFT feature extraction"'
categories: []
date: '2008-04-01'
lastmod: 2020-12-27T11:32:00+08:00
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
publishDate: '2020-12-27T03:32:00.617858Z'
publication_types:
- '1'
abstract: Scale invariant feature transform (SIFT) is an approach for extracting distinctive
  invariant features from images, and it has been successfully applied to many computer
  vision problems (e.g. face recognition and object detection). However, the SIFT
  feature extraction is compute-intensive, and a real-time or even super-real-time
  processing capability is required in many emerging scenarios. Nowadays, with the
  multi- core processor becoming mainstream, SIFT can be accelerated by fully utilizing
  the computing power of available multi-core processors. In this paper, we propose
  two parallel SIFT algorithms and present some optimization techniques to improve
  the implementation 's performance on multi-core systems. The result shows our improved
  parallel SIFT implementation can process general video images in super-real-time
  on a dual-socket, quad-core system, and the speed is much faster than the implementation
  on GPUs. We also conduct a detailed scalability and memory performance analysison
  the 8-core system and on a 32-core chip multiprocessor (CMP) simulator. The analysis
  helps us identify possible causes of bottlenecks, and we suggest avenues for scalability
  improvement to make this application more powerful on future large-scale multi-
  core systems.
publication: '*2008 IEEE International Symposium on Parallel and Distributed Processing*'
doi: 10.1109/IPDPS.2008.4536131
---
