---
layout: archive
title: "Tableau作品集"
date: 2018-1-2T11:40:45-04:00
modified:
excerpt: "作品集"
tags: []
image: 
  feature: 
---

- <a href="https://public.tableau.com/profile/.71971766#!/vizhome/xinxikeshihua/1_1?publish=yes" target="_blank">![数据分析.png](https://i.loli.net/2018/01/07/5a523c30f2438.png)</a>


其他作品
<div class="tiles">
{% for post in site.categories.visualization %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles 把所有categories 有 visualization 的列出来-->
