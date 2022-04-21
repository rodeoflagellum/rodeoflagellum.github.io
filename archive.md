---
layout: page
title: Archive
permalink: /archive/
---

---

{% assign postsByYear =
    site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in postsByYear %}
  <h2>{{ year.name }}</h2>
    <ul>
      {% for post in year.items %}
        <li><a href="{{ post.url }}">{{ post.title }}-{{ post.date }}</a></li>
      {% endfor %}
    </ul>
{% endfor %}
