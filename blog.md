---
layout: default
permalink: "/Blog"
title: "BLOG"
---

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
