--- 
layout: default
title: ’‚ «ª∂”≠“≥£°
---
* πßœ≤£°
°°{% for post in site.posts %}

°°  {{ post.date | date_to_string }} 
  {{ site.baseurl }}({{ post.url }})

  {{ post.title }}
°°°°°°°°
  {% endfor %}