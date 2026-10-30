---
layout: full-width
title: Publications
permalink: /publications/
order: 3
---

<header class="page-header">
  <p class="kicker">Publications</p>
  <h1 class="page-title">Published papers</h1>
  <p class="page-lede">Peer-reviewed articles, newest first. See also my <a href="https://orcid.org/0000-0002-8926-3311">ORCID profile</a>.</p>
</header>

<ul class="pub-list">
  {% for pub in site.data.publications %}
    {% include publication.html pub=pub %}
  {% endfor %}
</ul>
