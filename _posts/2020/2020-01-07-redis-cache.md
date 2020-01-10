---
layout: post
title: 分布式缓存架构的技术选择
no-post-nav: true
category: share
tags: [share]
---

解决系统并发问题及数据库压力

流量突发时，对系统的影响及防护

电商系统对于秒杀、活动等情形时，必须使用缓存机制来解决对数据库的访问。

系统的演进：

- 当前系统流量的改进方案
- 迁移到redis的同步方案
- redis与noSql全内存处理方案的架构



