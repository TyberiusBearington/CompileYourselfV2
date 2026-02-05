---
layout: default
title: Home
---

# Compile Yourself

Its never too late to compile yourself. Find the time to get your version 2 out there.

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
