---
layout: page
title: research
permalink: /research/
description: Research experiences, projects, publications, and scholarly development.
nav: true
nav_order: 3
---

_Research statement will be added as the dossier develops._

## Current / IU Research

<div class="projects">
{% assign items = site.projects | where: "category", "research" | where: "section", "current" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>

## Earlier / Funded Research

<div class="projects">
{% assign items = site.projects | where: "category", "research" | where: "section", "earlier" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>

## Publications & Presentations

See the [Publications]({{ '/publications/' | relative_url }}) page and [CV]({{ '/cv/' | relative_url }}) for the full scholarly record.
