---
layout: default
title: Dustin Lo, Horrible Cop
---

## Posts

<ul class="posts">

	  {% for post in site.posts %}
	    <li><span>{{ post.date | date_to_string }}</span> » <a href="/cs5520_project{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	  {% endfor %}
	</ul>
