---
layout: archive
title: "论文发表"
permalink: /zh/publications/
author_profile: true
lang: "zh"
switch_url: /publications/
---

{% if author.googlescholar %}
  您也可以在<u><a href="{{author.googlescholar}}">我的 Google Scholar 主页</a></u>上找到我的论文。
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
