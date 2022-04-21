---
layout: page
title: Archive
permalink: /archive/
---

<!-- From here: https://stackoverflow.com/questions/19086284/jekyll-liquid-templating-how-to-group-blog-posts-by-year?noredirect=1&lq=1 -->


{% for post in site.posts %}
  {% assign currentdate = post.date | date: "%Y" %}
  {% if currentdate != date %}
    {% unless forloop.first %}
    </ul>

    {% endunless %}

    <h1 id="y{{post.date | date: "%Y"}}">{{ currentdate }}</h1>

    <ul>
    {% assign date = currentdate %}
  {% endif %}
    <li>{{ post.title }}</li>
  {% if forloop.last %}</ul>{% endif %}
{% endfor %}
