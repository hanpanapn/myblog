---
layout: page
title: 一个入坑物联网开发的前端工程师 | 擅长前端开发，了解点Node,还了解点Linux、树莓派、物联网开发、智能家居…
---

<section>
{% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
{% endfor %}
</section>
