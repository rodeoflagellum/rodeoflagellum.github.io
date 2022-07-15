---
layout: post
title: Archive
permalink: /archive/
image: /assets/2022/archive/urja-bhatt-TuvollqROb8-unsplash.jpg
---

<!-- From here: https://stackoverflow.com/questions/19086284/jekyll-liquid-templating-how-to-group-blog-posts-by-year?noredirect=1&lq=1 -->

---

{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
{% for year in postsByYear %}
  <h2> {{ year.name }} </h2>
  {% assign postsByMonth = year.items | group_by_exp:"post", "post.date | date: '%B'" %}

{% for month in postsByMonth %}
### {{ month.name }}
<ul>
  {% for post in month.items %}
    {% if post.category != "Draft" %}
      {% if post.modified %}

        {% if post.description %}
        <li>
          <b><a href="{{ post.url }}">{{ post.title }}</a></b> ({{ post.date | date_to_long_string }} - {{ post.modified | date_to_long_string }})<br><p style="margin-left: 20px"><em>{{ post.description }}</em></p>
        </li>
        {% else %}
        <li>
          <b><a href="{{ post.url }}">{{ post.title }}</a></b> ({{ post.date | date_to_long_string }})
        </li>
        {% endif %}
      {% else %}
        <li>
          <b><a href="{{ post.url }}">{{ post.title }}</a></b> ({{ post.date | date_to_long_string }})<br><p style="margin-left: 20px"><em>{{ post.description }}</em></p>
        </li>
      {% endif %}
      {% endif %}

    
  {% endfor %}
</ul>

{% endfor %}
{% endfor %}

<br>

---

<br>

The [cover photo][cover_photo]{:target="_blank"} for this page was likely taken by [Phoebe K][author]{:target="_blank"}. I found the photo on [Unsplash][unsplash]{:target="_blank"}. To my knowledge, my use of this photo is permissible under Unsplash's [license][lic]{:target="_blank"}:
> Unsplash grants you an irrevocable, nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use photos from Unsplash for free, including for commercial purposes, without permission from or attributing the photographer or Unsplash. This license does not include the right to compile photos from Unsplash to replicate a similar or competing service.


[cover_photo]: https://unsplash.com/photos/5EfHF-iN0m4 "https://unsplash.com/photos/5EfHF-iN0m4"

[author]: https://unsplash.com/@raven_k "https://unsplash.com/@raven_k"

[lic]: https://unsplash.com/license "https://unsplash.com/license"

[unsplash]: https://unsplash.com/ "https://unsplash.com/"
