---
title: maxAlone Lab
---

# Service Area
* this github space serves as a crossover for the study assets behind the demos in the Tangram.page space
* visit my linkedIN profile for more information and to know what I am focused on

![](./video/target_transfer.mov)


* * *

## Posts
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

* * *

## Tags
{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}