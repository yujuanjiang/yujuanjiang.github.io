---
permalink: /blogs/
title: "Blog"
last_modified_at: 2020-07-15T09:26:22-04:00
toc: false
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
