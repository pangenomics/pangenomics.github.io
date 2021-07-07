---
layout: page
title: Projects
description: >
  Short introductions to the research projects of the lab
hide_description: false
permalink: /projects/
---

{% for project in site.projects %}
  <h2>{{ project.name }} </h2>
  <p>{{ project.content | markdownify }}</p>
{% endfor %}