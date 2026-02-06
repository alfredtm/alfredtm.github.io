---
layout: default
title: Home
---

<ul class="posts">
{% for post in site.posts %}
  <li>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    <span class="date">{{ post.date | date: "%B %d, %Y" }}</span>
  </li>
{% endfor %}
</ul>
