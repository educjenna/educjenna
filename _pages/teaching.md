---
layout: page
title: teaching
permalink: /teaching/
description: University teaching, K–12 teaching, and teacher professional development.
nav: true
nav_order: 4
---

_Teaching statement will be added as the dossier develops._

<div class="projects">
{% assign items = site.projects | where: "category", "teaching" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
