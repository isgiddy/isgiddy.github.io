---
layout: default
title: Categories
permalink: /categories/
---

{% assign categories = site.posts | map: 'categories' | join: ',' | split: ',' | uniq %}
{% for category in categories %}
  <h2>{{ category | capitalize }}</h2>
  <ul>
    {% for post in site.posts %}
      {% if post.categories contains category %}
        <li><a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%b %-d, %Y" }})</li>
      {% endif %}
    {% endfor %}
  </ul>
{% endfor %}
