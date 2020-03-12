---
layout: page
title: Proj
description: 人越学越觉得自己无知
keywords: 项目, Proj
comments: false
menu: 项目
permalink: /proj/
---

> 记多少命令和快捷键会让脑袋爆炸呢？

<ul class="listing">
{% for proj in site.proj %}
{% if proj.title != "Proj Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ proj.url }}">{{ proj.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
