---
layout: page
title: Instructors
nav_order: 2
description: A listing of all the course staff members.
---

# Instructors

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>

# GSIs

<div class="role">
  {% assign instructors = site.staffers | where: 'role', 'GSI' %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
