---
title: Blogger
tags: [test]
categories: [test]
poster:
  topic: Github api监控更新
  headline: 监控各个博客项目的更新~
  caption: Stellar,NotionNext....
  color: white
date: 2022-12-12 14:28:35
description:
cover: https://image.66619.eu.org/file/c5115ca242e2511f795b8.png
banner:
---

监控stellar主题
{% timeline api:https://api.github.com/repos/xaoxuu/hexo-theme-stellar/releases?per_page=2 %}
{% endtimeline %}

监控NotionNext
{% timeline api:https://api.github.com/repos/tangly1024/NotionNext/releases?per_page=2 %}
{% endtimeline %}