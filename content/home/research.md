---
# An instance of the Featurette widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: featurette

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

title: 研究内容
subtitle:

# Showcase personal skills or business features.
# - Add/remove as many `feature` blocks below as you like.
# - For available icons, see: https://wowchemy.com/docs/page-builder/#icons
feature:
- description: 专注于内存虚拟化、容器技术、内存管理等相关技术
  icon: docker
  icon_pack: custom
  name: 虚拟化技术
- description: 主要针对1) 修复性能优化方案、2) 磁盘阵列技术、3) 扩容算法及4) 分布式容错机制等方面进行研究。
  icon: recovery
  icon_pack: custom
  name: 容错与灾备
- description: 研究基于LSM-Tree的Key-Value存储系统的读写机制，优化其在不同应用场景下的读写性能
  icon: kvstore
  icon_pack: custom
  name: KV存储
- description: 对社交网络图等图数据的分析处理，主要包含图计算和图系统两个研究方向
  icon: graph
  icon_pack: custom
  name: 图分析
- description: 研究分布式机器学习系统，提升分布式训练性能，主要针对分布式场景下的迭代计算流程进行优化
  icon: AI
  icon_pack: custom
  name: 分布式机器学习
- description: 研究分布式场景下的存储问题，主要是对于分布式存储系统、分布式文件系统的问题优化
  icon: distributed
  icon_pack: custom
  name: 分布式存储系统


# Uncomment to use emoji icons.
#- icon: ":smile:"
#  icon_pack: "emoji"
#  name: "Emojiness"
#  description: "100%"  

# Uncomment to use custom SVG icons.
# Place custom SVG icon in `assets/images/icon-pack/`, creating folders if necessary.
# Reference the SVG icon name (without `.svg` extension) in the `icon` field.
#- icon: "your-custom-icon-name"
#  icon_pack: "custom"
#  name: "Surfing"
#  description: "90%"
---