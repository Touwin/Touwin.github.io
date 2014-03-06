---
title: "Lud's Dev Blog"
layout: default
---



<a href="/a-propos/">À propos</a>


<ul class="posts">
  {% for post in site.posts limit: 5 %}
    <li><span>{{ post.date | date_to_string }}</span> &mdash; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
