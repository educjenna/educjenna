---
layout: page
title: teaching
permalink: /teaching/
description: University teaching, teacher professional development, and K–12 instructional innovation.
nav: true
nav_order: 4
---

_Teaching statement will be added as the dossier develops._

## University Teaching

<div class="projects">
{% assign items = site.projects | where: "category", "teaching" | where: "section", "university" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>

## Teacher Professional Development

<div class="projects">
{% assign items = site.projects | where: "category", "teaching" | where: "section", "teacher-ed" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>

## K–12 Teaching & Instructional Innovation

<div class="projects">
{% assign items = site.projects | where: "category", "teaching" | where: "section", "k12" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
