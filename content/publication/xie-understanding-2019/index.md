---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Understanding Persuasion Cascades in Online Product Rating Systems
subtitle: ''
summary: ''
authors:
- Hong Xie
- Yongkun Li
- John C. S. Lui
tags: []
categories: []
date: '2019-07-01'
lastmod: 2020-10-16T11:09:08+08:00
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
publishDate: '2020-10-16T03:09:08.310248Z'
publication_types:
- '2'
abstract: 'Online product rating systems have become an indispensable component for
  numerous web services such as Amazon, eBay, Google play store and TripAdvisor. One
  functionality of such systems is to uncover the product quality via product ratings
  (or reviews) contributed by consumers. However, a well-known psychological phenomenon
  called “messagebased persuasion” lead to “biased” product ratings in a cascading
  manner (we call this the persuasion cascade). This paper investigates: (1) How does
  the persuasion cascade influence the product quality estimation accuracy? (2) Given
  a real-world product rating dataset, how to infer the persuasion cascade and analyze
  it to draw practical insights? We first develop a mathematical model to capture
  key factors of a persuasion cascade. We formulate a high-order Markov chain to characterize
  the opinion dynamics of a persuasion cascade and prove the convergence of opinions.
  We further bound the product quality estimation error for a class of rating aggregation
  rules including the averaging scoring rule, via the matrix perturbation theory and
  the Chernoff bound. We also design a maximum likelihood algorithm to infer parameters
  of the persuasion cascade. We conduct experiments on the data from Amazon and TripAdvisor,
  and show that persuasion cascades notably exist, but the average scoring rule has
  a small product quality estimation error under practical scenarios.'
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence*'
url_pdf: https://www.aaai.org/ojs/index.php/AAAI/article/view/4490
doi: 10.1609/aaai.v33i01.33015490
---
