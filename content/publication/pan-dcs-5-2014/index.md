---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'DCS5: Diagonal Coding Scheme for Enhancing the Endurance of SSD-Based RAID-5
  Systems'
subtitle: ''
summary: ''
authors:
- Yubiao Pan
- Yongkun Li
- Yinlong Xu
- Weitao Zhang
tags:
- '"Arrays"'
- '"Complexity theory"'
- '"data redundancy schemes"'
- '"DCS5 scheme"'
- '"Decoding"'
- '"diagonal coding scheme"'
- '"Encoding"'
- '"Endurance"'
- '"I/O parallelism"'
- '"input-output parallelism"'
- '"large-scale storage systems"'
- '"Layout"'
- '"load balancing"'
- '"parallel programming"'
- '"RAID"'
- '"redundant array of independent disks"'
- '"resource allocation"'
- '"solid-state drives"'
- '"Solid-state Drives"'
- '"SSD-Based RAID-5 systems"'
- '"SSD-based storage systems"'
- '"Strips"'
- '"System-level Wear-leveling"'
- '"trace-driven evaluation"'
categories: []
date: '2014-08-01'
lastmod: 2020-10-16T11:09:17+08:00
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
publishDate: '2020-10-16T03:09:16.893235Z'
publication_types:
- '1'
abstract: Solid-state drives (SSDs) have been widely deployed in large-scale storage
  systems. To guarantee high reliability for SSD-based storage systems, it still requires
  data redundancy schemes, e.g., RAID schemes. Traditional RAID-5 shows its benefits
  in load-balancing and I/O parallelism, and so it is still the first choice for enhancing
  the reliability of SSD RAID arrays. However, some SSDs under the RAID-5 configuration
  may age much faster than others because of the non-uniformity of workloads, which
  makes them be worn out very quickly and so decreases the endurance of SSD-based
  RAID arrays. To address this problem, we develop a diagonal coding scheme, DCS5,
  to improve the wear-leveling among devices in an SSD-based RAID-5 array. DCS5 can
  efficiently improve the array endurance if accesses are aligned with the stripe
  size, i.e., When data symbols in the same stripe receive the same number of writes,
  while the number could be different for different stripes. To relax the above assumption,
  we further propose an enhanced scheme which is called as DCS5+. DCS5+ can improve
  the wear-leveling among devices under general access patterns via triggering different
  responses to different kinds of requests. We conduct extensive trace-driven evaluations
  based on real-world workloads, and results show that our coding scheme efficiently
  enhances the endurance of SSD-based RAID-5 arrays.
publication: '*2014 9th IEEE International Conference on Networking, Architecture,
  and Storage*'
doi: 10.1109/NAS.2014.16
---
