---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Mitigating Packet Reordering in FiWi Networks
subtitle: ''
summary: ''
authors:
- Shiliang Li
- Jianping Wang
- Chunming Qiao
- Yinlong Xu
tags:
- '"Algorithms"'
- '"Dispersion"'
- '"Network topology"'
- '"Optical networks"'
- '"Optical wireless communication"'
- '"Passive optical networks"'
categories: []
date: '2011-02-01'
lastmod: 2020-12-27T11:32:03+08:00
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
publishDate: '2020-12-27T03:32:03.106942Z'
publication_types:
- '2'
abstract: In an integrated fiber and wireless (FiWi) access network consisting of
  a wireless subnetwork and an optical subnetwork, multipath routing may be applied
  in the wireless subnetwork to improve throughput. Due to different delays along
  multiple paths, packets may arrive at the destination out of order, which may cause
  Transmission Control Protocl (TCP) performance degradation. In this paper, we propose
  two mechanisms to improve in-order departure of packets from the optical line terminal
  (OLT) in a FiWi network and enhance the TCP performance. We first propose an effective
  scheduling algorithm at the OLT to ensure possible in-order packet arrivals at the
  destination. We then design a dynamic bandwidth allocation (DBA) scheme in the optical
  subnetwork (i.e., an Ethernet passive optical network) that gives higher priorities
  to flows that may trigger fast retransmit and fast recovery in upstream bandwidth
  allocation. Simulation results show that both the proposed scheduling algorithm
  and the DBA scheme are effective in improving the TCP performance.
publication: '*Journal of Optical Communications and Networking*'
url_pdf: https://www.osapublishing.org/jocn/abstract.cfm?uri=jocn-3-2-134
doi: 10.1364/JOCN.3.000134
---
