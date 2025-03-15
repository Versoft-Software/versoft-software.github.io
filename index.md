---
layout: default
title: "Free95 a FOSS Windows Alternative"
---

# Welcome to the Free95 blog

## Latest Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> - {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>