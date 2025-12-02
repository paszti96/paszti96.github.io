---
layout: default
title: "Blog"
permalink: /blog/
---

<ul class="post-list">
  {% for post in site.posts %}
    <li class="post-list-item">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span class="post-meta">· {{ post.date | date: "%b %-d, %Y" }}</span>
      {% if post.excerpt %}
        <p class="post-excerpt">{{ post.excerpt | strip_html | truncate: 160 }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>
