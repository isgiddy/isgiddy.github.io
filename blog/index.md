---
layout: full-width
title: Blog
permalink: /blog/
order: 3
---

<h1 class="content-listing-header sans">topics of interest</h1>
<ul class="content-listing">
  {% for post in site.posts %}
    {% if post.categories contains "musings" %}
      <li class="listing">
        <hr class="slender">
        <a href="{{ post.url | relative_url }}">
          <h3 class="contrast">{{ post.title }}</h3>
        </a>
        <br>
        <span class="smaller">{{ post.date | date: "%B %-d, %Y" }}</span><br/>
        <div>{{ post.excerpt | strip_html | truncatewords: 40}}</div>
      </li>
    {% endif %}
  {% endfor %}
</ul>