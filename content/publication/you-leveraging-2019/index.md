---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Leveraging Array Mapped Tries in KSM for Lightweight Memory Deduplication
subtitle: ''
summary: ''
authors:
- Lingjing You
- Yongkun Li
- Fan Guo
- Yinlong Xu
- Jinzhong Chen
- Liu Yuan
tags:
- '"AMT-KSM"'
- '"array mapped tries"'
- '"Array Mapped Tries"'
- '"Arrays"'
- '"Bandwidth"'
- '"cloud computing"'
- '"Cloud computing"'
- '"content-based page comparison"'
- '"content-based page sharing mechanism"'
- '"duplicate pages"'
- '"file organisation"'
- '"hardware resources"'
- '"Indexes"'
- '"Kernel"'
- '"kernel same-page merging"'
- '"KSM"'
- '"lightweight memory deduplication"'
- '"Linux"'
- '"memory bandwidth"'
- '"Memory Deduplication"'
- '"memory page"'
- '"merging"'
- '"Merging"'
- '"paged storage"'
- '"red-black trees"'
- '"storage management"'
- '"tree data structures"'
- '"virtual machines"'
categories: []
date: '2019-08-01'
lastmod: 2020-10-16T11:09:06+08:00
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
publishDate: '2020-10-16T03:09:06.378230Z'
publication_types:
- '1'
abstract: In cloud computing, how to use limited hardware resources to meet the increasing
  demands has become a major issue. KSM (Kernel Same-page Merging) is a content-based
  page sharing mechanism used in Linux that merges equal memory pages, thereby significantly
  reducing memory usage and increasing the density of virtual machines or containers.
  However, KSM introduces a large overhead in CPU and memory bandwidth usage due to
  the use of red-black trees and content-based page comparison. To reduce the deduplication
  overhead, in this paper, we propose a new design called AMT-KSM, which leverages
  array mapped tries to realize lightweight memory deduplication. The basic idea is
  to divide each memory page into multiple segments and use the concatenated strings
  of the hash values of segments as indexed keys in the tries. By doing this, we can
  significantly reduce the time required for searching duplicate pages as well as
  the number of page comparisons. We conduct experiments to evaluate the performance
  of our design, and results show that compared with the conventional KSM, AMT-KSM
  can reduce up to 44.9% CPU usage and 31.6% memory bandwidth usage.
publication: '*2019 IEEE International Conference on Networking, Architecture and
  Storage (NAS)*'
doi: 10.1109/NAS.2019.8834730
---
