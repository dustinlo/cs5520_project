---
layout: default
title: Dustin Lo, Horrible Cop
---

## Posts

<ul class="posts">
	  {% for post in site.posts %}
    <li><span>{{ post.url | relative_url }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
