---
title: "Research"
permalink: /research/
author_profile: true
---

{% for research in site.research %}
  <article class="archive__item">
    <h2 class="archive__item-title">
      <a href="{{ research.url }}">{{ research.title }}</a>
    </h2>

    {% if research.type %}
      <p><strong>{{ research.type }}</strong></p>
    {% endif %}

    {% if research.venue %}
      <p>{{ research.venue }}</p>
    {% endif %}

    {% if research.date %}
      <p><small>{{ research.date | date: "%Y" }}</small></p>
    {% endif %}

    {{ research.excerpt }}
  </article>
{% endfor %}
