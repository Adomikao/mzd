---
layout: default
title: 毛泽东选集  第五卷
category: 4
---

<ul>
  <ul>
    {% assign page_list = site.categories['5'] | sort:"date" %}
    {% for post in page_list %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</ul>