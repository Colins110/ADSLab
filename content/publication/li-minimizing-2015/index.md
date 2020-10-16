---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Minimizing coordination in replicated systems
subtitle: ''
summary: ''
authors:
- Cheng Li
- João Leitão
- Allen Clement
- Nuno Preguiça
- Rodrigo Rodrigues
tags: []
categories: []
date: '2015-04-01'
lastmod: 2020-10-16T11:09:21+08:00
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
publishDate: '2020-10-16T03:09:20.687368Z'
publication_types:
- '1'
abstract: 'Replication has been widely adopted to build highly scalable services,
  but this goal is often compromised by the coordination required to ensure application-specific
  properties such as state convergence and invariant preservation. In this paper,
  we propose a principled mechanism to minimize coordination in replicated systems
  via the following components: a) a notion of restriction over pairs of operations,
  which captures the fact that the two operations must be ordered w.r.t. each other
  in any partial order; b) a generic consistency model which, given a set of restrictions,
  requires those restrictions to be met in all admissible partial orders; c) principles
  for identifying a minimal set of restrictions to ensure the above properties; and
  d) a coordination service that dynamically maps restrictions to the most efficient
  coordination protocols. Our preliminary experience with example applications shows
  that we are able to determine a minimal coordination strategy.'
publication: '*Proceedings of the First Workshop on Principles and Practice of Consistency
  for Distributed Data*'
url_pdf: https://doi.org/10.1145/2745947.2745955
doi: 10.1145/2745947.2745955
---
