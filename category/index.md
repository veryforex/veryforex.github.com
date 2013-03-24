---
layout: default
title: Indicators index
name: index
category: category
---

Indicators Index
========================

<ul>
{% for post in site.posts limit:5 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>