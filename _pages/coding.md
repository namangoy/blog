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
  {% for post in site.posts.coding %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
