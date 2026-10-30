---
layout: full-width
title: Blog
permalink: /blog/
order: 4
---

<header class="page-header">
  <p class="kicker">Blog</p>
  <h1 class="page-title">Topics of interest</h1>
  <p class="page-lede">Notes on science, society and life as a scientist, written as I think them through.</p>
</header>

<ul class="post-list">
  {% for post in site.posts %}
    {% if post.categories contains "musings" %}
      {% include post-card.html post=post words=40 %}
    {% endif %}
  {% endfor %}
</ul>
