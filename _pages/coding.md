---
permalink: "/coding/"
title:  "Coding"
header:
  teaser: 
  overlay_image: 
  overlay_filter: 
sidebar:
  nav: "coding"
author: Naman Goyal
---

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
