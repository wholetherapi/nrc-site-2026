---
layout: default
title: Northwind Research Collective
---

# Northwind Research Collective

We build and deploy open field instruments for coastal and shelf observing.
The project catalogue below lists every item currently registered with the
field programme office.

{% for item in site.projects %}
- [{{ item.title }}]({{ item.url }}) &mdash; {{ item.status }} &mdash; {{ item.programme }}
{% endfor %}
