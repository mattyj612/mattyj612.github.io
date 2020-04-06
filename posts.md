---
layout: page
title: Posts
permalink: /posts/
description:
published: true
---

<ul class="post-list">
  {% for post in site.posts %}
  <li>
      <h2><a class="post-title" href="{{ post.url }}">{{ post.title }}</a></h2>
      <p class="post-meta">{{ post.date | date: '%B %-d, %Y' }}</p>
      <p>{{ post.description }}</p>
    </li>
  {% endfor %}
</ul>
