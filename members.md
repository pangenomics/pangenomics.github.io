---
layout: page
title: Members
description: >
  Short introduction to the member of the lab
hide_description: true
permalink: /members/
---

{% for staff_member in site.members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}