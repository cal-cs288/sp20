---
layout: page
title: Staff
nav_order: 3
description: A listing of all the course staff members.
---

# Staff

Staff information is stored in the `_staffers` directory and rendered according to the layout file, `_layouts/staffer.html`.

<div class="role">
  {% assign instructors = site.staffers %}
  {% for staffer in instructors %}
  {{ staffer }}
  {% endfor %}
</div>
