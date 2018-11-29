---
layout: post
title: Blog
permalink: /blog/
---
This is my blog.  While it is a place to share some projects, mostly I want to keep a record for myself of how I did certain things and solved certain problems.  Then I can use it as a reference.

<div>
	  {% for post in site.posts %}
	      <li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	        {% endfor %}

</div>