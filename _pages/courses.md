---
title: "Courses"
permalink: /courses/
author_profile: true
---

{% for course in site.courses %}
  <article class="archive__item">
    <h2 class="archive__item-title">
      <a href="{{ course.url }}">{{ course.title }}</a>
    </h2>

    {% if course.type %}
      <p><strong>{{ course.type }}</strong></p>
    {% endif %}

    {% if course.venue %}
      <p>{{ course.venue }}</p>
    {% endif %}

    {% if course.date %}
      <p><small>{{ course.date | date: "%Y" }}</small></p>
    {% endif %}

    {{ course.excerpt }}
  </article>
{% endfor %}
