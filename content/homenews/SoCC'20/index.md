---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "实验室一项成果被云计算领域顶级会议SoCC收录"
summary: ""
#authors: []
tags: []
categories: []
date: 2020-8-19T16:21:58+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
近期，在实验室老师们、同学和微软亚洲研究院合作者们的共同努力下，ADSL实验室又一项成果被云计算领域顶级会议 SoCC 录用。向各位参与研究工作的老师、同学、合作者表示祝贺，并感谢你们一直以来的辛勤工作和付出！

本项成果涉及AI 系统领域中优化加速图神经网络在大规模图数据集上的采样训练，摘要如下:

论文: PaGraph: Scaling GNN Training on Large Graphs via Computation-aware Caching and Partitioning. Zhiqi Lin (USTC), Cheng Li (USTC), Youshan Miao (MSRA), Yunxin Liu (MSRA), Yinlong Xu (USTC). ACM Symposium on Cloud Computing 2020 (SoCC ’20)

概要: 图神经网络已经广泛用于探索和处理图结构数据。对于大规模图数据集，现有的图神经网络框架利用 GPU 等加速器并结合图采样和批处理方式来有效地训练图神经网络。然而，现有的技术面临着数据加载时间长、可拓展性差等问题。本文提出 PaGraph, 在单机多 GPU 机器上采用图缓存策略和图分割策略来有效提升图神经网络训练性能。图缓存策略用于在 GPU 上缓存频繁访问的图数据信息，从而大幅度减少数据加载的时间，有效提升训练性能。在多 GPU 训练场景下，采用为图神经网络定制的图分割策略，并配合图缓存机制，极大程度地提升训练可拓展性。


