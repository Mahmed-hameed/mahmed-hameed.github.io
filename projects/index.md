---
title: "Projects"
permalink: /projects/
layout: single
---

Below are selected projects across IT and Cyber Security.

<div class="grid__wrapper">
{% assign all_projects = site.projects | sort: 'date' | reverse %}
{% for p in all_projects %}
  <article class="archive__item" itemscope itemtype="https://schema.org/CreativeWork">
    <h2 class="archive__item-title" itemprop="headline">
      <a href="{{ p.url | relative_url }}">{{ p.title }}</a>
    </h2>
    {% if p.excerpt or p.summary %}
    <p class="archive__item-excerpt" itemprop="description">{{ p.excerpt | default: p.summary }}</p>
    {% endif %}
    <p class="archive__item-meta">
      {% if p.category %}<strong>Area:</strong> {{ p.category | capitalize }} · {% endif %}
      {% if p.tags %}<strong>Tags:</strong> {{ p.tags | join: ", " }}{% endif %}
    </p>
  </article>
{% endfor %}
</div>
