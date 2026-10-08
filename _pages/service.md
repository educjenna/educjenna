---
layout: page
title: service
permalink: /service/
description: Leadership and service to the program, profession, and educational community.
nav: true
nav_order: 5
---

_Service statement will be added as the dossier develops._

<div class="projects">
{% assign items = site.projects | where: "category", "service" | sort: "importance" %}
<div class="row row-cols-1 row-cols-md-3">
{% for project in items %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
