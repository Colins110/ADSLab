---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'DCS: Diagonal Coding Scheme for Enhancing the Endurance of SSD-Based RAID
  Arrays'
subtitle: ''
summary: ''
authors:
- Yubiao Pan
- Yongkun Li
- Yinlong Xu
- Biaobiao Shen
tags:
- '"Arrays"'
- '"Complexity theory"'
- '"data redundancy scheme"'
- '"DCS scheme"'
- '"diagonal coding scheme"'
- '"encoding"'
- '"Encoding"'
- '"Endurance"'
- '"Organizations"'
- '"RAID"'
- '"RAID-5"'
- '"RAID-6"'
- '"Redundancy"'
- '"redundant array of independent disks"'
- '"redundant array of independent disks (RAID)"'
- '"redundant configuration"'
- '"Reed-Solomon codes"'
- '"solid-state drives"'
- '"solid-state drives (SSDs)"'
- '"SSD-based RAID arrays"'
- '"SSD-based storage systems"'
- '"system-level wear-leveling"'
categories: []
date: '2016-08-01'
lastmod: 2020-10-16T11:09:30+08:00
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
publishDate: '2020-10-16T03:09:29.776499Z'
publication_types:
- '2'
abstract: To guarantee high reliability, solid-state drive (SSD)-based storage systems
  require data redundancy schemes, e.g., redundant array of independent disks (RAID)
  schemes. Traditional RAID-5, RAID-6, and Reed-Solomon codes can tolerate one, two,
  and an arbitrary number of device failures, respectively. However, some SSDs under
  those redundant configurations may age much faster than others because of the high
  skewness and locality of workloads. The uneven aging rates may make some SSDs wear
  out very quickly and decrease the endurance of SSD-based RAID arrays. To address
  this problem, we first come up with a diagonal coding scheme (DCS) by distributing
  the updating dependencies evenly among devices to improve the system-level wear-leveling.
  DCS can efficiently improve the array endurance if requests are aligned with the
  stripe size, i.e., when data symbols in the same stripe receive the same number
  of writes, while the number could be different for different stripes. To relax the
  above assumption, we further propose an enhanced scheme, DCS+. With a buffer design,
  DCS+ can improve the wear-leveling among devices under general access patterns via
  triggering different responses to different kinds of requests. We conduct extensive
  trace-driven evaluations based on real-world workloads, and results show that our
  design efficiently enhances the endurance of SSD-based RAID arrays.
publication: '*IEEE Transactions on Computer-Aided Design of Integrated Circuits and
  Systems*'
doi: 10.1109/TCAD.2015.2504333
---
