---
layout: page
title: Labs
permalink: /labs/
---

Hands-on lab write-ups: configurations, commands, what broke and how I fixed it.

{% assign items = site.categories.lab %}
{% if items and items.size > 0 %}
<ul>
{% for post in items %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small></li>
{% endfor %}
</ul>
{% else %}
<p><em>Coming soon.</em></p>
{% endif %}
