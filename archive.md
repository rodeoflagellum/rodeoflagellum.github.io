---
layout: page
title: Archive
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
      <a href="{{ post.url }}">{{ post.title }}</a>
      <br>
    </li>
  {% endfor %}
</ul>

{% endfor %}
{% endfor %}
