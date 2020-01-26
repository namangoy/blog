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
Recent posts
<hr>
<ul>
{% for post in site.categories.Coding limit:10 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}
<ul>
