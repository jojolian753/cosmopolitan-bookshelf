---
layout: page
title: Cosmopolitan Bookshelf
tagline: Literature and philosophy books from around the world!
---
{% include JB/setup %}

Group's description goes here

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

