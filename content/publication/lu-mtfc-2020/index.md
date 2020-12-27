---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'MTFC: A Multi-GPU Training Framework for Cube-CNN-based Hyperspectral Image
  Classification'
subtitle: ''
summary: ''
authors:
- Y. Lu
- K. Xie
- G. Xu
- H. Dong
- C. Li
- T. Li
tags:
- '"Graphics processing units"'
- '"Training"'
- '"Computation-to-GPU Mapping Mechanism"'
- '"Cube-CNN"'
- '"Data mining"'
- '"Feature extraction"'
- '"Hyperspectral Image Classification"'
- '"Hyperspectral imaging"'
- '"Machine learning"'
- '"Multi Streams"'
- '"Multi-GPUs"'
- '"Task analysis"'
categories: []
date: '2020-01-01'
lastmod: 2020-12-27T11:31:59+08:00
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
publishDate: '2020-12-27T03:31:58.955582Z'
publication_types:
- '2'
abstract: Hyperspectral images (HSI) classification has been a research hotspot in
  the remote sensing field. Deep learning methods such as Cube-CNN have been applied
  to address the HSI classification problem. However, mainstream frameworks exist
  a performance gap to train Cube-CNN, since they are not designed for processing
  high dimensional data like HSI. To close this gap, we propose a Multi-GPU Training
  Framework (MTFC) for Cube-CNN-based HSI classification. We first design a Parallel
  Neighbor Pixel Extraction (PNPE) algorithm for efficiently generating 3-dimensional
  cube samples from raw data. Then, to fully exploit massive GPU parallelism and realize
  unique characteristics of HSI and Cube-CNN, we employ optimizations in MTFC such
  as task division, fine-grained mapping between tasks and GPU thread blocks, shared
  memory usage reduction, etc. Finally, to further improve training speed, we take
  advantage of CUDA streams and multiple GPUs to train a mini-batches of data samples
  simultaneously. An extensive set of experiments highlights that MTFC constantly
  outperforms the two baselines Caffe and Theano for all measured metrics across all
  system configurations, while offering the same level of classification accuracy.
  The speedup is up to 3.6x when using a single GPU and MTFC can achieve a rough linear
  scaling on multiple GPUs.
publication: '*IEEE Transactions on Emerging Topics in Computing*'
doi: 10.1109/TETC.2020.3016978
---
