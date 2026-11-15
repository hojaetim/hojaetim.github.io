---
layout: page
title: GRC
permalink: /grc/
---

Governance, risk and compliance: how technical controls map to policies and frameworks.

{% assign items = site.categories.grc %}
{% if items and items.size > 0 %}
<ul>
{% for post in items %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>({{ post.date | date: "%Y-%m-%d" }})</small></li>
{% endfor %}
</ul>
{% else %}
<p><em>Coming soon.</em></p>
{% endif %}
