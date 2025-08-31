---
layout: archive
title: "News Archive"
permalink: /all_news/
author_profile: false
---

{% for post in site.posts %}
{% if post.tags contains 'news' %}
<ul class="news-list">
  <li class="news-item">
    <span class="news-date">{{ post.date | date: "%b %d, %Y" }}</span>
    <a class="news-title" href="{{ post.url }}">{{ post.title }}</a>
  </li>
</ul>
{% endif %}
{% endfor %}