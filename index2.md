---
layout: plain
title: Index2
---

test Index2


<ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

Hint: When GitHub Jekyll config - associate *.yml files with Scrapbook (actually from JDT)