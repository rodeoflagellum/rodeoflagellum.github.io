---
layout: post
title: Archive
date: 2022-04-21 10:00:00 -0400
permalink: /archive/
tags: [list, site]
image: /assets/2022/archive/urja-bhatt-TuvollqROb8-unsplash.jpg
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
      <b><a href="{{ post.url }}">{{ post.title }}</a></b> ({{ post.date | date_to_long_string }})<br> <em>{{ post.desc }}</em><br>
    </li>
  {% endfor %}
</ul>

{% endfor %}
{% endfor %}

---

## [Notes](#notes)

### [Cover Photo](#cover-photo)

The [cover photo][cover_photo]{:target="_blank"} for this page was likely taken by [Phoebe K][author]{:target="_blank"}. I found the photo on [Unsplash][unsplash]{:target="_blank"}. To my knowledge, my use of this photo is permissible under Unsplash's [license][lic]{:target="_blank"}: "_Unsplash grants you an irrevocable, nonexclusive, worldwide copyright license to download, copy, modify, distribute, perform, and use photos from Unsplash for free, including for commercial purposes, without permission from or attributing the photographer or Unsplash. This license does not include the right to compile photos from Unsplash to replicate a similar or competing service._"


[cover_photo]: https://unsplash.com/photos/5EfHF-iN0m4 "https://unsplash.com/photos/5EfHF-iN0m4"

[author]: https://unsplash.com/@raven_k "https://unsplash.com/@raven_k"

[lic]: https://unsplash.com/license "https://unsplash.com/license"

[unsplash]: https://unsplash.com/ "https://unsplash.com/"
