---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "ADSL实验室16级博士生陈友旭顺利通过博士学位答辩"
subtitle: ""
summary: "11月4日下午2点30分，在中国科学技术大学东校区高性能中心402会议室，举行ADSL实验室16级博士生陈友旭同学的博士论文毕业答辩。"
authors: []
tags: []
categories: []
date: 2019-11-29T10:02:16+08:00
lastmod: 2019-11-29T10:02:16+08:00
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

&ensp;&ensp;&ensp;&ensp;11月4日下午2点30分，在中国科学技术大学东校区高性能中心402会议室，举行ADSL实验室16级博士生陈友旭同学的博士论文毕业答辩。陈友旭同学在攻读博士学位阶段，研究工作主要聚焦在分布式文件系统元数据管理问题，并分别从元数据预取机制、元数据服务器集群负载均衡策略和元数据管理方案三个方面，探究现有分布式文件系统元数据管理问题中存在的问题，并加以优化来提升系统元数据存取性能。论文的主要工作和创新点如下：

1. 设计了一种基于数据关联性的元数据预取机制SMeta，采用语法分析机制提取数据关联性，并将其存储在元数据扩展属性结构中，复用了现有元数据同步机制同时降低关联性更新开销。
2. 提出了一种元数据服务器集群负载均衡策略Fim，在元数据服务器节点内采用消息队列机制传输消息以提升MDS通信速度，结合集群物理架构，引入节点内优先迁移方式来提升元数据迁移速度。在目标迁移目录选择方案中，结合系统负载特征动态选择迁移目录以提升元数据迁移效率。并且采用迁移消息与客户端请求并发处理机制和热迁移方式，避免了迁移操作对客户端元数据请求的阻塞。
3. 提出了一种混合元数据管理方案SmartM2，针对多节点和节点内多MDS的元数据服务器集群架构，在节点间使用子树划分方案管理元数据保留了文件系统目录结构，在节点内多MDS间使用哈希映射方案提升负载均衡性能，实现元数据管理中目录局部性与负载均衡性能的高效权衡。

&ensp;&ensp;&ensp;&ensp;答辩委员会各位老师高度认可陈友旭同学所选研究课题的理论意义、应用价值和研究成果，并针对其研究工作中的方法设计和系统实现等方面的问题，提出了很多宝贵的建议，为陈友旭同学后序的研究工作提供了广泛的思路。经答辩委员会无记名投票，一致通过陈友旭同学的博士学位论文答辩，并建议授予博士学位。答辩结束后，答辩委员会与陈友旭同学进行合影。

&ensp;&ensp;&ensp;&ensp;陈友旭同学表示：“很感谢各位评审老师和答辩老师用其专业的知识给予论文宝贵的修改意见，感谢ADSL实验室许老师、李诚老师、李永坤老师和吕敏老师对我工作上的指导和建议！ ADSL是一个有爱的大家庭，在最好的年华教会了我成长，感谢实验室对我的培养！祝愿ADSL未来成果多多，越来越好！”