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
Recent posts
<hr>
<ul>
{% for post in site.categories.Updates limit:10 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<ul>

