---
layout: page
title: Monthly Reports 
tagline: morota@UNL
---
{% include JB/setup %}

Monthly reports from my [group](http://morotalab.org) at UNL are also available at [Archive](http://morotalab.org/monthlyReports/archive.html).

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


