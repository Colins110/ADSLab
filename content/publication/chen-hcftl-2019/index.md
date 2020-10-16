---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'HCFTL: A Locality-Aware Page-Level Flash Translation Layer'
subtitle: ''
summary: ''
authors:
- Hao Chen
- Cheng Li
- Yubiao Pan
- Min Lyu
- Yongkun Li
- Yinlong Xu
tags:
- '"active mapping entries"'
- '"Automation"'
- '"built-in DRAM"'
- '"cache space"'
- '"cache storage"'
- '"cached mapping table"'
- '"Computer science"'
- '"DRAM chips"'
- '"dynamic translation pages"'
- '"flash memories"'
- '"FTL performance"'
- '"HCFTL"'
- '"hot-clusterity FTL"'
- '"index structure"'
- '"Indexes"'
- '"Loading"'
- '"locality-aware page-level flash translation layer"'
- '"logical-to-physical address translation"'
- '"mapping information"'
- '"Random access memory"'
- '"solid state drives"'
- '"SSD capacity"'
- '"Standards"'
- '"state-of-the-art FTL schemes"'
- '"temporal localities"'
- '"Time factors"'
categories: []
date: '2019-03-01'
lastmod: 2020-10-16T11:09:07+08:00
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
publishDate: '2020-10-16T03:09:07.137234Z'
publication_types:
- '1'
abstract: The increasing capacity of SSDs requires a large amount of built-in DRAM
  to hold the mapping information of logical-to-physical address translation. Due
  to the limited size of DRAM, existing FTL schemes selectively keep some active mapping
  entries in a Cached Mapping Table (CMT) in DRAM, while storing the entire mapping
  table on flash. To improve the CMT hit ratio with limited cache space on SSDs, in
  this paper, we propose a novel FTL, a hot-clusterity FTL (HCFTL) that clusters mapping
  entries recently evicted from the cache into dynamic translation pages (DTPs). Given
  the temporal localities that those hot entries are likely to be visited in near
  future, loading DTPs will increase the CMT hit ratio and thus improve the FTL performance.
  Furthermore, we introduce an index structure to speedup the lookup of mapping entries
  in DTPs. Our experiments show that HCFTL can improve the CMT hit ratio by up to
  41.1% and decrease the system response time by up to 33.3%, compared to state-of-the-art
  FTL schemes.
publication: '*2019 Design, Automation Test in Europe Conference Exhibition (DATE)*'
doi: 10.23919/DATE.2019.8715252
---
