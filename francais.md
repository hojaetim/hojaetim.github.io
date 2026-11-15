---
layout: page
title: Français
permalink: /francais/
---

Mes notes en français sur la cybersécurité et les réseaux.

{% assign items = site.categories.francais %}
{% if items and items.size > 0 %}
<ul>
{% for post in items %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small></li>
{% endfor %}
</ul>
{% else %}
<p><em>Coming soon.</em></p>
{% endif %}
