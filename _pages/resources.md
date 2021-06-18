---
layout: page
title: Resources
sidebar_link: true
permalink: resources
---


### Selected articles, chapters, reports
  
<ul>
{% for pub in site.data.pubs %}
<li>
 <a href="{{ pub.link }}">{{ pub.title }}</a>{% if pub.authors %},{% endif %} <em>{{ pub.authors }} ({{ pub.year }})</em>
</li>
{% endfor %}
</ul>

