---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Efficient Parity Update for Scaling RAID-like Storage Systems
subtitle: ''
summary: ''
authors:
- Dongdong Sun
- Yinlong Xu
- Yongkun Li
- Si Wu
- Chengjin Tian
tags:
- '"Disksim"'
- '"Fault tolerance"'
- '"Fault tolerant systems"'
- '"High performance computing"'
- '"input-output throughput"'
- '"Layout"'
- '"online scaling scenario"'
- '"parity update"'
- '"RAID"'
- '"RAID-like storage systems"'
- '"RCW scheme"'
- '"read-modify-write scheme"'
- '"read-reconstruct-write scheme"'
- '"redundant array of independent disks"'
- '"RMW scheme"'
- '"scaling approach"'
- '"storage capacity"'
- '"storage management"'
- '"Throughput"'
- '"Time factors"'
categories: []
date: '2016-08-01'
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
publishDate: '2020-10-16T03:09:17.286230Z'
publication_types:
- '1'
abstract: It is inevitable to scale RAID systems with the increasing demand of storage
  capacity and I/O throughput. When scaling RAID systems, we will always need to update
  parity to maintain the reliability of the storage systems. There are two schemes,
  read-modify-write (RMW) and read-reconstruct-write (RCW), to update parity. However
  most existing scaling approaches simply use RMW to update parity. While in many
  scenarios for existing scaling approaches, RCW performs better in terms of the number
  of scaling I/Os. In this paper, we propose an algorithm, called EPU, to analyze
  which of RCW and RMW is better for a scaling scenario and select the more efficient
  one to save the scaling I/Os. We apply EPU to online scaling scenarios and further
  use two optimizations, I/O overlap and access aggregation, to enhance the online
  scaling performance. Using Scale-CRS, one of the existing scaling approaches, as
  an example, we show via numerical studies that Scale-CRS+EPU reduces the amount
  of scaling I/Os over the traditional Scale-CRS in many scaling cases. To justify
  the online efficiency of EPU, we implement both Scale-CRS+EPU and Scale-CRS in a
  simulator with Disksim as a working module. Through extensive experiments, we show
  that Scale-CRS+EPU reduces the scaling time and the online response time of user
  requests over Scale-CRS.
publication: '*2016 IEEE International Conference on Networking, Architecture and
  Storage (NAS)*'
doi: 10.1109/NAS.2016.7549400
---
