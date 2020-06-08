---
layout: post
title: "Diary"
permalink: /diary/
---

{% for post in site.tags["diary"] %}
<h2>
  <a href="{{ post.url | relative_url }}">
    {{ post.date | date: '%Y/%m' }}: {{ post.title }}
  </a>
</h2>
{% endfor %}
