---
layout: page
title: Publications
description: >
  Key publications of the Pangenomics lab and it's PI
hide_description: false
permalink: /publications/
---
Selected Publications of the Pangenomics lab and it's PI
For a complete list of Daniel's publications see [Google Scholar](http://scholar.google.com/citations?user=q4JtNUkAAAAJ)

{% for publication in site.publications %}
  <h2>{{ publication.name }} </h2>
  <p>{{ publication.content | markdownify }}</p>
{% endfor %}