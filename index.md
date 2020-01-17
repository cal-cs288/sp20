---
layout: home
title: Home
nav_order: 0
description: >-
    Just the Class is a modern, highly customizable, responsive Jekyll theme
    for developing course websites.
---

# An Artificial Intelligence Approach to Natural Language Processing
{: .mb-2 }
Spring 2020
{: .mb-0 .fs-6 .text-grey-dk-000 }

{% if site.announcements %}
{{ site.announcements.last }}
<a href="{{ site.baseurl }}/announcements" class="btn btn-outline fs-3">
  All Announcements
</a>
{% endif %}

{% for module in site.modules %}
{{ module }}
{% endfor %}

