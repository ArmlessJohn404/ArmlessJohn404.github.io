---
layout: default
title:
description: My Blog
---
{% for item in site.posts %}
  <article class="blog-post">
    <h2 class="post-title"> {{ item.title }}</h2>
    <h3 class="post-title"> {{ item.date }} </h3>
    {{ item }}
  </article>
{% endfor %}
