---
layout: page
title: substars!!!
tagline: doesn't use subversion despite the prefix similarities, crazy right
---
{% include JB/setup %}

Maybe I'll write stuff about programming sometimes.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


