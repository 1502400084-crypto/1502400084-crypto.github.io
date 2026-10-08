---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

## 关于我
大家好，我是刘晨。目前就读于福州大学，对人工智能和高性能计算充满兴趣。

## 兴趣方向
- 深度学习与AI算法
- 高性能计算（HPC）
- Linux系统与开源工具
- AI Infra：希望在将来深入探索分布式训练，大模型推理加速等前沿工程。

## 学习计划
目前正在学习c++基础、Git协作与Linux基础，计划在未来几个月内深入了解python、pytorch、并行计算和CUDA编程，争取早日参与到超算团队的实际项目中，积累实践经验。
