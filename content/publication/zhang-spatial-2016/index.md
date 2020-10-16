---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A Spatial Mashup Service for Efficient Evaluation of Concurrent $k$ -NN Queries
subtitle: ''
summary: ''
authors:
- Detian Zhang
- Chi-Yin Chow
- Qing Li
- Xinming Zhang
- Yinlong Xu
tags:
- '"location-based services"'
- '"Mashups"'
- '"Optimization"'
- '"Query processing"'
- '"road networks"'
- '"Roads"'
- '"Servers"'
- '"Spatial mashups"'
- '"Time factors"'
- '"web mapping services"'
- '"κ-NN queries"'
categories: []
date: '2016-08-01'
lastmod: 2020-10-16T11:09:35+08:00
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
publishDate: '2020-10-16T03:09:35.445500Z'
publication_types:
- '2'
abstract: Although the travel time is the most important information in road networks,
  many spatial queries, e.g., $k$ -nearest-neighbor ( $k$ -NN) and range queries,
  for location-based services (LBS) are only based on the network distance. This is
  because it is costly for an LBS provider to collect real-time traffic data from
  vehicles or roadside sensors to compute the travel time between two locations. With
  the advance of web mapping services, e.g., Google Maps, Microsoft Bing Maps, and
  MapQuest Maps, there is an invaluable opportunity for using such services for processing
  spatial queries based on the travel time. In this paper, we propose a server-side
  Spatial M ashup Service (SMS) that enables the LBS provider to efficiently evaluate
  $k$ -NN queries in road networks using the route information and travel time retrieved
  from an external web mapping service. Due to the high cost of retrieving such external
  information, the usage limits of web mapping services, and the large number of spatial
  queries, we optimize the SMS for a large number of $k$ -NN queries. We first discuss
  how the SMS processes a single $k$ -NN query using two optimizations, namely, direction
  sharing and parallel requesting. Then, we extend them to process multiple concurrent
  $k$ -NN queries and design a performance tuning tool to provide a trade-off between
  the query response time and the number of external requests and more importantly,
  to prevent a starvation problem in the parallel requesting optimization for concurrent
  queries. We evaluate the performance of the proposed SMS using MapQuest Maps, a
  real road network, real and synthetic data sets. Experimental results show the efficiency
  and scalability of our optimizations designed for the SMS.
publication: '*IEEE Transactions on Computers*'
doi: 10.1109/TC.2015.2485215
---
