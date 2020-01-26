---
permalink: "/coding/"
layout: single
title:  "Coding"
header:
  teaser: 
  overlay_image: 
  overlay_filter: 
sidebar:
  nav: "coding"
author: Naman Goyal
author_profile: true
---
Placeholder

<ul>
  {% for post in site.categories.Coding limit:10 %}
    <li>
      <h1> <a href="{{ post.url }}">{{ post.title }}</a></h1>
      {{ post.content }}
    </li>
  {% endfor %}
  
</ul>
