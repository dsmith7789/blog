---
layout: page
title: "Taskflow"
permalink: /taskflow/
---

Taskflow is a cloud task processing platform I'm building — this series documents the design and implementation as I go.

## Posts

<ul>
{% assign sorted = site.taskflow | sort: "order" %}
{% for doc in sorted %}
  <li><a href="{{ doc.url | relative_url }}">{{ doc.title }}</a></li>
{% endfor %}
</ul>