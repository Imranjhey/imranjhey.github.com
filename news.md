---
layout: default
title: "News"
---
I will be blogging and  keeping all interesting notes (mathematics or general stuffs)

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
