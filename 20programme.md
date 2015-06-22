---
layout: page
title: Program
permalink: /program/
---

While we are waiting for a more detailed outline of the programme,
here is a rough sketch of the overall structure to aid you in the
travel planning.

Conference schedule

Tue, Sep. 1, 2015
  Registration and Helpdesk 9:00 - 18:00
  Pre-conference workshops  9:30 - 17:00
  Public opening lecture   17:30

Tue, Sep. 2, 2015
  Registration and Helpdesk 9:00 - 18:00
  Opening                   9:15
  Session presentations, plenary lecture and poster session  9:30 - 17:30
  Conference Banquet       18:00
  
Tue, Sep. 3, 2015  
  Registration and Helpdesk 9:00 - 17:00
  Session presentations and plenary lecture  9:30 - 17:00
  Closing                  17:00 - 17:30
  

<div id="posts">
  <ul>
    {% for post in site.posts %}
	{% if post.category == "program" %}
      <li><span>{{ post.date | date_to_string }}</span> - <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
	{% endif %}    
{% endfor %}
  </ul>
</div>
