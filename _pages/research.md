---
layout: page
title: research
permalink: /research/
description: Research experiences, projects, publications, and scholarly development.
nav: true
nav_order: 3
---

_Research statement will be added as the dossier develops._

<div class="projects">
{% assign items = site.projects | where: "category", "research" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
