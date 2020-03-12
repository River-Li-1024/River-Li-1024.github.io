---
layout: page
title: Books
description: 人越学越觉得自己无知
keywords: 项目, Books
comments: false
menu: 项目
permalink: /books/
---

> 记多少命令和快捷键会让脑袋爆炸呢？

<ul class="listing">
{% for book in site.books %}
{% if book.title != "Book Template" %}
<li class="listing-item"><a href="{{ site.url }}{{ book.url }}">{{ book.title }}</a></li>
{% endif %}
{% endfor %}

</ul>
