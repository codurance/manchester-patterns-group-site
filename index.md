---
layout: default
title:  "Index title"
---

# Index h1

Index content

<ul>
  {% for post in site.posts %}
    <li>
      <a href="/manchester-patterns-group-site{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
