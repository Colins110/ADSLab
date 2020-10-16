---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Balanced Parity Update Algorithm with Queueing Length Awareness for RAID Arrays
subtitle: ''
summary: ''
authors:
- Youxu Chen
- Yinlong Xu
- Yongkun Li
- Jun Xu
tags:
- '"Arrays"'
- '"balanced parity update algorithm"'
- '"Bandwidth"'
- '"BPU"'
- '"Heuristic algorithms"'
- '"I/O queues"'
- '"parity chunk update"'
- '"Parity Update"'
- '"Performance"'
- '"Prototypes"'
- '"Queue"'
- '"Queueing analysis"'
- '"queueing length awareness"'
- '"RAID"'
- '"RAID arrays"'
- '"RCW"'
- '"read-construct-write"'
- '"read-modify-write"'
- '"redundant arrays of inexpensive disks"'
- '"RMW"'
- '"Skewness"'
- '"storage management"'
- '"System performance"'
- '"Time factors"'
categories: []
date: '2016-12-01'
lastmod: 2020-10-16T11:09:15+08:00
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
publishDate: '2020-10-16T03:09:15.378232Z'
publication_types:
- '1'
abstract: In parity-based RAID arrays, to update a data chunk, the corresponding parity
  chunk(s) must be updated accordingly so as to keep data consistency and availability.
  To achieve this, either read-modify-write (RMW) or read-construct-write (RCW) could
  be used. Traditional parity update algorithm always selects the one requiring fewer
  pre-reads so as to reduce the total number of I/Os, but it may aggravate the skewness
  of I/O queues on disks, and thus degrades the system performance. In this paper,
  we propose a balanced parity update algorithm with queueing length awareness, BPU,
  which takes the number of pre-reads, the skewness of I/O queues on disks, and real-time
  workload into consideration when selecting RCW or RMW to update parity chunks. We
  implement a prototype system with BPU to evaluate its performance. Experimental
  results show that the length of I/O queues on disks in a RAID array may be highly
  skewed when using traditional parity update algorithm, and thus severely degrades
  the system performance. With BPU, we can reduce the average response time by up
  to 10%. We also study the performance of BPU under different system configurations,
  and provide multiple insights for adjusting the parameters of BPU so as to optimize
  its performance.
publication: '*2016 IEEE 22nd International Conference on Parallel and Distributed
  Systems (ICPADS)*'
doi: 10.1109/ICPADS.2016.0111
---
