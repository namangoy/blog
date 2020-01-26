---
permalink: "/updates/"
layout: single
title:  "Updates"
header:
  teaser: 
  overlay_image: 
  overlay_filter: 
sidebar:
  nav: "updates"
author: Naman Goyal
author_profile: true
---
Placeholder

<ul>
  {% for post in site.categories.Updates %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
