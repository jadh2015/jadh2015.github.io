---
layout: page
title: Program
permalink: /program/
---

Program (to be announced)

The program will consist of a pre-conference workshop to be held on
Sep. 1st and two days of academic paper and poster presentations as
well as keynote lectures on Sep 2 and 3. 

Details will be posted in June.


<div id="posts">
  <ul>
    {% for post in site.posts %}
	{% if post.category == "program" %}
      <li><span>{{ post.date | date_to_string }}</span> - <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}    
{% endfor %}
  </ul>
</div>
