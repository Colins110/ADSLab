---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "实验室一项成果（SpanDB）被存储领域顶级会议 FAST 接收"
summary: "经过持续两年的努力，我们实验室和卡塔尔QCRI马晓松老师合作的SpanDB被计算机存储系统领域顶级国际会议 FAST 2020 (CCF A类) 收录。"
#authors: []
tags: []
categories: []
date: 2020-12-16T16:21:58+08:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
经过持续两年的努力，我们实验室和卡塔尔QCRI马晓松老师合作的SpanDB被计算机存储系统领域顶级国际会议 FAST 2020 (CCF A类) 收录。向各位参与研究工作的老师、同学、合作者表示祝贺。

这项研究工作利用包括Intel Optane SSD在内的混合介质加速基于LSM-tree的主流健值存储系统。与以往工作不同，我们选择了比非持久性内存NVRAM更便宜且应用更广泛的NVMe SSD，目标是把此类SSD的全部潜力都释放出来，做到物尽其用。最终，加速效果在尾延迟、平均延迟、吞吐率等方面相较业界最新的成果有较为明显的提升。

近年来，在实验室负责人许胤龙教授的带领下，我们实验室在计算机系统特别是在健值数据库方向有了长期稳定的积累，这项工作的发表标志着我们已经突破了“成熟度壁垒”，科研实力向着更高水平迈进。

此项工作得到了国家自然科学基金重点项目、科技部重点研发课题、双一流学科建设、111协同创新、合肥市创新计划的资助，得到了国家高性能计算中心（合肥）、安徽省高性能计算重点实验室、超算中心的平台支持！

论文题目：SpanDB: A Fast, Cost-Effective LSM-tree Based KV Store on Hybrid Storage

论文摘要：键值（KV）存储广泛地应用在许多关键的应用程序和服务中。它们可以进行快速的内存处理，但是仍然经常受到 I/O 性能的限制。高速商用 NVMe SSD 的出现推动了基于超低延迟和高带宽SSD的新型KV系统的设计。但是，要切换到全新的数据结构并将整个数据库扩展到高端SSD，需要大量的资金投入。作为一种折衷方案，基于LSM树的 SpanDB，利用包括 fast NVMe SSD的混合介质加速基于LSM-tree的主流健值存储系统。与以往工作不同，SpanDB选择了比NVRAM便宜且应用更广泛的NVMe SSD，且目标是把此类SSD的全部潜能都释放出来。 SpanDB允许用户将大量数据托管在更便宜和更大的SSD（甚至HDD）上，同时将预写日志（WAL）和LSM树的顶层重新定位到更小，更快的高端 NVMe SSD 。为了更好地利用此NVMe SSD，SpanDB通过SPDK提供了高速并行WAL写入，并启用了异步请求处理以减轻线程间同步开销，并有效地使用基于轮询的I/O。最终，加速效果在尾延迟、平均延迟、吞吐率等方面相较业界最新的成果有较为明显的提升。
