---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Popularity-Based Online Scaling for RAID Systems Under General Settings
subtitle: ''
summary: ''
authors:
- Chengjin Tian
- Yongkun Li
- Si Wu
- Jinzhong Chen
- Liu Yuan
- Yinlong Xu
tags:
- '"Bandwidth"'
- '"Data locality"'
- '"Interference"'
- '"Layout"'
- '"Measurement"'
- '"online scaling"'
- '"redundant arrays of independent disks (RAIDs) systems"'
- '"Reed-Solomon codes"'
- '"Silicon"'
- '"Time factors"'
categories: []
date: '2020-10-01'
lastmod: 2020-10-16T11:09:24+08:00
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
publishDate: '2020-10-16T03:09:23.916372Z'
publication_types:
- '2'
abstract: The ever-increasing demand of storage capacity and system performance leads
  to the scaling requirement in redundant arrays of independent disks (RAID)-structured
  storage systems. Existing approaches mainly focus on minimizing data migration in
  offline scenario, but not consider the user accesses issued by applications. However,
  in online scenario, the scaling I/Os and user I/Os usually interfere with each other,
  and result in significant performance degradation. Thus, it is of big significance
  to develop an efficient online scaling scheme to mitigate the impact of I/O interference.
  In this paper, we propose popularity-based online scaling (POS), which exploits
  workload locality by scaling storage zones with high popularity in a higher priority.
  POS can efficiently alleviate the interference between scaling I/Os and user I/Os,
  and it is also general enough to scale various RAID systems like RAID-0, RAID-5,
  and RAID-6. It can also be readily deployed atop various conventional RAID scaling
  approaches to improve their performance. To demonstrate the effectiveness of POS,
  we implement various conventional RAID scaling approaches, and also implement POS
  on top of these approaches for comparison. Extensive simulations with real-world
  workloads show that POS can efficiently reduce the response time of user requests
  and scaling I/Os, and also improves the sequentiality of data accesses.
publication: '*IEEE Transactions on Computer-Aided Design of Integrated Circuits and
  Systems*'
doi: 10.1109/TCAD.2019.2930580
---
