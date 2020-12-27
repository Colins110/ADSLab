---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Finding complex concurrency bugs in large multi-threaded applications
subtitle: ''
summary: ''
authors:
- Pedro Fonseca
- Cheng Li
- Rodrigo Rodrigues
tags:
- '"concurrency bugs"'
- '"latent bugs"'
- '"linearizability"'
- '"semantic bugs"'
categories: []
date: '2011-04-01'
lastmod: 2020-12-27T11:32:01+08:00
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
publishDate: '2020-12-27T03:32:01.662650Z'
publication_types:
- '1'
abstract: Parallel software is increasingly necessary to take advantage of multi-core
  architectures, but it is also prone to concurrency bugs which are particularly hard
  to avoid, find, and fix, since their occurrence depends on specific thread interleavings.
  In this paper we propose a concurrency bug detector that automatically identifies
  when an execution of a program triggers a concurrency bug. Unlike previous concurrency
  bug detectors, we are able to find two particularly hard classes of bugs. The first
  are bugs that manifest themselves by subtle violation of application semantics,
  such as returning an incorrect result. The second are latent bugs, which silently
  corrupt internal data structures, and are especially hard to detect because when
  these bugs are triggered they do not become immediately visible. Pike detects these
  concurrency bugs by checking both the output and the internal state of the application
  for linearizability at the level of user requests. This paper presents this technique
  for finding concurrency bugs, its application in the context of a testing tool that
  systematically searches for such problems, and our experience in applying our approach
  to MySQL, a large-scale complex multi-threaded application. We were able to find
  several concurrency bugs in a stable version of the application, including subtle
  violations of application semantics, latent bugs, and incorrect error replies.
publication: '*Proceedings of the sixth conference on Computer systems*'
url_pdf: https://doi.org/10.1145/1966445.1966465
doi: 10.1145/1966445.1966465
---
