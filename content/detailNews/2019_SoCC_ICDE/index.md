---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "实验室三项成果分别被云计算领域顶级会议SoCC、数据库领域顶级会议 ICDE收录"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2019-10-14T23:33:04+08:00
lastmod: 2019-10-14T23:33:04+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
近期，在实验室老师、同学们和其他合作者们的共同努力下，ADSL 实验室又有三项成果分别被云计算领域顶级会议ACM SoCC(CCF B类)、数据库领域顶级会议ICDE(CCF A类)录用。

首先，向各位参与研究工作的老师、同学、合作者表示祝贺，并感谢你们一直以来的辛勤工作和付出！

三项成果分别涉及容器优化、GPU调度、键值存储系统，摘要如下：

论文一：HP-Mapper: A High Performance Storage Driver for Docker. Fan Guo, Yongkun Li, Min Lv, Yinlong Xu, John C.S. Lui, University of Science and Technology of China. To appear in the Proceedings of the ACM Symposium on Cloud Computing 2019 (SoCC 2019), Santa Cruz, CA, USA.

概要：Docker containers are widely deployed to provide lightweight virtualization, and they have many desirable features such as ease of deployment and near bare-metal performance. However, both the performance and cache efficiency of containers are still limited by their storage drivers due to the coarse-grained copy-on-write operations, and the large amount of redundancy in both I/O requests and page cache. To improve the I/O performance and cache efficiency of containers, we develop HPMapper, a high performance storage driver for Docker containers. HP-Mapper provides a two-level mapping strategy to support fine-grained copy-on-write with low overhead, and an efficient interception method to reduce redundant I/Os. Furthermore, it uses a novel cache management mechanism to reduce duplicate cached data. Experiment results with our prototype system show that HPMapper significantly reduces copy-on-write latency due to its finer-grained copy-on-write scheme. Moreover, HPMapper can also reduce 65.4% cache usage on average due to elimination of duplicated data. As a result, HPMapper improves the throughput of real-world workloads by up to 39.4%, and improves the startup speed of containers by 2.0X.

论文二：DCUDA: Dynamic GPU Scheduling with Live Migration Support. Fan Guo, Yongkun Li, John C.S. Lui, Yinlong Xu, University of Science and Technology of China. To appear in the Proceedings of the ACM Symposium on Cloud Computing 2019 (SoCC 2019), Santa Cruz, CA, USA.

概要：In clouds and data centers, GPU servers which consist of multiple GPUs are widely deployed. Current state-of-the-art GPU scheduling algorithm are “static” in assigning applications to different GPUs. These algorithms usually ignore the dynamics of the GPU utilization and are often inaccurate in estimating resource demand before assigning/running applications, so there is a large opportunity to further load balance and to improve GPU utilization. Based on CUDA (Compute Unified Device Architecture), we develop a runtime system called DCUDA which supports “dynamic” scheduling of running applications between multiple GPUs. In particular, DCUDA provides a realtime and lightweight method to accurately monitor the resource demand of applications and GPU utilization. Furthermore, it provides a universal migration facility to migrate “running applications” between GPUs with negligible overhead. More importantly, DCUDA transparently supports all CUDA applications without changing their source codes. Experiments with our prototype system show that DCUDA can reduce 78.3% of overloaded time of GPUs on average. As a result, for different workloads consisting of a wide range applications we studied, DCUDA can reduce the average execution time of applications by up to 42.1%. Furthermore, DCUDA also reduces 13.3% energy in the light load scenario.

论文三：UniKV: Toward High-Performance and Scalable KV Storage in Mixed Workloads via Unified Indexing. Zhang Qiang, Yongkun Li, Patrick P. C. Lee, Yinlong Xu, Qiu Cui, Liu Tang, University of Science and Technology of China. To appear in the Proceedings of the 36th IEEE International Conference on Data Engineering (ICDE 2020), Dallas, TX, USA.

概要：Persistent key-value (KV) stores are mainly designed based on the Log-Structured Merge-tree (LSM-tree), which suffer from large read and write amplifications, especially when KV stores grow in size. Existing design optimizations for LSM-tree-based KV stores often make certain trade-offs and fail to simultaneously improve both the read and write performance on large KV stores without sacrificing scan performance. We design UniKV, which unifies the key design ideas of hash indexing and the LSM-tree in a single system. Specifically, UniKV leverages data locality to differentiate the indexing management of KV pairs. It also develops multiple techniques to tackle the issues caused by unifying the indexing techniques, so as to simultaneously improve the performance in reads, writes, and scans. Experiments show that UniKV significantly outperforms several state-of-the-art KV stores (e.g., LevelDB, RocksDB, HyperLevelDB, and PebblesDB) in overall throughput under readwrite mixed workloads.

![](icde2020.png)

最后，再次感谢实验室各位老师、同学以及合作者的辛勤工作和不懈努力，希望ADSL实验室的各位成员能够继续努力，在计算机系统的研究上取得新突破！
