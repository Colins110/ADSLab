---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "三项成果被计算机系统重要国际会议USENIX ATC和HotStorage收录"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2018-04-22T23:42:24+08:00
lastmod: 2018-04-22T23:42:24+08:00
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
在实验室老师、同学及其他合作者的共同努力下，本实验室三项成果分别被计算机系统领域重要国际会议USENIX ATC 2018（CCF A类）和计算机存储领域重要workshop HotStorage收录。**其中USENIX ATC长论文两篇，HotStorage论文一篇。向所有合作者、参研老师和同学表示祝贺！也向他们表示衷心感谢！**

这三项重要成果涉及系统领域的两个研究热点：**键值数据库（KV store）和分布式一致性**。这些研究成果的核心目的都是要突破存储、计算、传输的瓶颈，使得系统架构更加优化，性能得到更大提升，以应对日益增长的互联网服务和智能计算对于高效能存储的客观需求。摘要如下：

论文一：*Fine-grained consistency for geo-replicated systems. Cheng Li (University of Science and Technology of China), Nuno Preguica (Nova University of Lisbon), Rodrigo Rodrigues (University of Lisbon). To appear in the Proceedings of USENIX ATC 2018. BOSTON, MA, USA.*

概要：互联网需要为来自世界各地的用户提供便捷的服务。为此，大部分的互联网服务提供商都采用用户数据跨地域备份技术（geo-replication）来拉近服务与用户的距离，使得用户请求可以在距离最近的服务器上得到响应。 但该技术背后存在着系统性能（用户请求时延和吞吐率）与跨地域数据一致性之间的尖锐矛盾。为了解决该矛盾，现有的技术将二者之间的取舍从系统层面拓展到操作层面，从而降低了维持一致性所需的跨数据中心并发控制的代价。然而，这些方法取舍粒度不够细且无法感知系统操作发生的频率，因而影响了互联网的便捷化服务水平。基于此，我们提出了一种新的可调控的一致性模型—— Partial Order-Restrictions consistency (or short, PoR consistency) —— 将系统一致性与性能之间的取舍与操作之间可见性约束（visibility restriction）联系起来，通过添加或者减少操作之间的可见性约束来增强或减弱整个系统的一致性，从而摆脱了一个系统只能选择单一一致性模型的局限。此外，为了提供基于PoR一致性模型的备份协议，我们实现了一个轻量级的并发控制服务Olisipo，该服务可根据操作出现的频率选择性能适配的控制协议，以减少运行时开销。我们将原型系统部署在亚马逊云计算平台的三个不同地域的备份节点上，并在该系统部署上运行RUBiS 评测工具。实验结果表明：相较前序工作（OSDI 2012、ATC 2014、PaPoC 2015和IEEE Data Bulletin. 2016），我们的一致性模型和原型系统可在添加少量约束的情况下，降低47.1%的用户请求延迟和提高21.5%的系统吞吐率。

论文二：*HashKV: Enabling Efficient Updates in KV Storage via Hashing. Helen H. W. Chan, Yongkun Li, Patrick P. C. Lee, Yinlong Xu. To appear in the Proceedings of USENIX ATC 2018. BOSTON, MA, USA.*

概要：Key-value (KV)系统已被广泛应用于多种应用场景，它主要采用LSM树的结构以实现高访问性能，但是KV系统仍面临严重的I/O放大问题。目前，业界提出了key和value分离的思想，通过仅将key存储于LSM树，而将value使用单独的存储管理来解决I/O放大问题。但是，现有的设计方案垃圾回收开销大，从而严重影响了KV系统的性能，尤其是针对写密集的负载。为了解决KV系统的I/O放大问题，我们沿用KV分离的思想，提出了HashKV系统，即使在写密集负载下仍能达到很好的写性能。HashKV主要采用基于Hash的数据分组思想，从而提升数据写入和垃圾回收的性能。与现有的KV分离方案相比，HashKV可以达到4.6倍的吞吐率，同时减少53.4%的数据写入量。

 

论文三：*ElasticBF: Fine-grained and Elastic Bloom Filter Towards Efficient Read for LSM-tree-based KV Stores.  Yueming Zhang, Yongkun Li, Fan Guo, Cheng Li, Yinlong Xu. To appear in the Proceedings of HotStorage 2018. BOSTON, MA, USA.*

概要：为满足数据密集型应用的高性能存储需求，依托于LSM-tree架构的键值数据库成为使用广泛的主流存储系统。该架构将键值对（key value pairs）存储在固定大小的SSTable文件内。为提高读性能，键值系统为每个SSTable配置一个布隆过滤器（Bloom filter），但是布隆过滤器的误报会引发额外的I/O 请求。且现有设计对系统内所有布隆过滤器采用统一设定，也不能对布隆过滤器误报率进行动态调整，其统一降低误报率的办法将会给系统环境带来巨大内存开销。基于此，本文提出弹性布隆过滤器机制（Elasitc Bloom Filter，ElasticBF）。ElasticBF 为每个SSTable构建 多个占用空间小的布隆过滤器，这些布隆过滤器机制存储于外存。对于访问频率高的SSTable，为其在内存中多加载一些布隆过滤器，而对访问频率低的SSTable，则少加载一些。而且，为了使过滤器的动态调整开销较小，我们扩展了多级队列这一数据结构，使用多级队列对布隆过滤器进行管理。因此，ElasticBF能够动态调节每个SSTable布隆过滤器的误报率和内存使用量，在内存开销相同的前提下，大大减少了 (实验中最高可达67%)读操作中因布隆过滤器误报引发的I/O请求，从而提高读性能。我们在LevelDB 的基础上实现了ElasticBF，并在服务器上进行了性能测试。实验结果显示，ElasticBF读吞吐量最高是 LevelDB的2.24 倍，且写性能几乎没有损失。

除了上述三项被接受的成果外，其他四篇投稿虽然被拒，但值得欣慰的是，每一篇稿件都收获了同行业国际专家不同程度的认可，以及极富建设性的修改意见。希望大家再接再厉，认真改进，完善成果，争取更大更好的成绩。
