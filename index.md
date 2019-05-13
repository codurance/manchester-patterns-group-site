---
layout: default
title:  "Index title"
---

# Index h1

Index content

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{{ site.url }}
