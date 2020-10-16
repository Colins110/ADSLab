---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'POS: A Popularity-based Online Scaling scheme for RAID-structured storage
  systems'
subtitle: ''
summary: ''
authors:
- Si Wu
- Yinlong Xu
- Yongkun Li
- Yunfeng Zhu
tags:
- '"access frequency"'
- '"Bandwidth"'
- '"Benchmark testing"'
- '"Computers"'
- '"data migration time"'
- '"Degradation"'
- '"FastScale with POS"'
- '"Frequency measurement"'
- '"measured popularity"'
- '"mixed scaling I/O"'
- '"online scheme"'
- '"performance degradation"'
- '"performance evaluation"'
- '"popularity-based online scaling scheme"'
- '"POS-FS"'
- '"RAID"'
- '"RAID scaling approach"'
- '"RAID-structured storage system"'
- '"real-system workload"'
- '"scaling process"'
- '"scaling requirement"'
- '"storage area"'
- '"storage capability"'
- '"storage space"'
- '"Time factors"'
- '"user request"'
- '"user response time"'
- '"user-level application access"'
categories: []
date: '2015-10-01'
lastmod: 2020-10-16T11:09:23+08:00
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
publishDate: '2020-10-16T03:09:23.032374Z'
publication_types:
- '1'
abstract: The ever-increasing demand of storage capability leads to scaling requirement
  in RAID-structured storage systems. Previous approaches to RAID scaling mainly focus
  on minimizing data migration, without considering the user-level application accesses.
  However, the mixed scaling I/Os and user accesses in practical systems will interfere
  with each other, which results in significant performance degradation of both the
  data migration time and the user response time. In this paper, we divide the whole
  storage space into multiple zones and measure the popularity (mainly using the metric
  of access frequency) of each zone. Based on the measured popularity, we propose
  an online scheme, namely Popularity-based Online Scaling (POS), to scale RAID-structured
  storage systems. The main idea of POS is to scale storage areas with high popularity
  first so as to better exploit workload locality. POS can efficiently alleviate the
  performance degradation of user response time and data migration time during the
  scaling process. It can be readily deployed atop various conventional RAID scaling
  approaches to improve their performance. To evaluate the performance of POS, we
  implement FastScale and FastScale with POS (POS-FS) in the same system. Through
  extensive benchmark studies on real-system workloads, we show that POS can efficiently
  reduce the response time to user requests and scaling I/Os and improve the sequentiality
  of data accesses.
publication: '*2015 33rd IEEE International Conference on Computer Design (ICCD)*'
doi: 10.1109/ICCD.2015.7357095
---
