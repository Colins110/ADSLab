---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Visigoth fault tolerance
subtitle: ''
summary: ''
authors:
- Daniel Porto
- João Leitão
- Cheng Li
- Allen Clement
- Aniket Kate
- Flavio Junqueira
- Rodrigo Rodrigues
tags: []
categories: []
date: '2015-04-01'
lastmod: 2020-10-16T11:09:20+08:00
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
publishDate: '2020-10-16T03:09:20.264379Z'
publication_types:
- '1'
abstract: We present a new technique for designing distributed protocols for building
  reliable stateful services called Visigoth Fault Tolerance (VFT). VFT introduces
  the Visigoth model, which makes it possible to calibrate the timing assumptions
  of a system using a threshold of slow processes or messages, and also to distinguish
  between non-malicious arbitrary faults and correlated attack scenarios. This enables
  solutions that leverage the characteristics of data center systems, namely their
  secure environment and predictable performance, in order to allow replicated systems
  to be more efficient with respect to the utilization of resources than those designed
  under asynchrony and Byzantine assumptions, while avoiding the need to make a system
  synchronous, or to restrict failure modes to silent crashes. We implemented a VFT
  protocol for a state machine replication library, and ran several benchmarks. Our
  evaluation shows that VFT has comparable performance to existing schemes and brings
  significant benefits in terms of the throughput per dollar, i.e., the server cost
  for sustaining a certain level of request execution.
publication: '*Proceedings of the Tenth European Conference on Computer Systems*'
url_pdf: https://doi.org/10.1145/2741948.2741979
doi: 10.1145/2741948.2741979
---
