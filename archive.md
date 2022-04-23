---
layout: post
title: Archive
date: 2022-04-21 10:00:00 -0400
permalink: /archive/
---

<!-- From here: https://stackoverflow.com/questions/19086284/jekyll-liquid-templating-how-to-group-blog-posts-by-year?noredirect=1&lq=1 -->


{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in postsByYear %}
  <h2> {{ year.name }} </h2>
  {% assign postsByMonth = year.items | group_by_exp:"post", "post.date | date: '%B'" %}

{% for month in postsByMonth %}
### {{ month.name }}
<ul>
  {% for post in month.items %}
    <li>
      <b><a href="{{ post.url }}">{{ post.title }}</a></b> ({{ post.date | date_to_long_string }}; <em>{{ post.desc }}</em>)<br>
    </li>
  {% endfor %}
</ul>

{% endfor %}
{% endfor %}
