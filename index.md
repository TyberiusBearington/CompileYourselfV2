---
layout: default
title: Home
---

# Welcome to My Blog

This is a simple blog site hosted on GitHub Pages.

## Recent Posts

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
      <a class="post-title" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <div class="post-excerpt">{{ post.excerpt }}</div>
    </li>
  {% endfor %}
</ul>
