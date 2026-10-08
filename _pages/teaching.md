---
layout: page
title: teaching
permalink: /teaching/
description: University teaching, teacher professional development, and K–12 instructional innovation.
nav: true
nav_order: 4
---

_Teaching statement will be added as the dossier develops._

<style>
.teaching-section { margin: 2.75rem 0 1.25rem; padding: 1rem 1.25rem; background: var(--global-code-bg-color); border-radius: .25rem; }
.teaching-section h2 { margin: 0; }
.teaching-entry { display: grid; grid-template-columns: minmax(210px, 31%) 1fr; gap: 2rem; padding: 1.65rem 0; border-bottom: 1px solid var(--global-divider-color); }
.teaching-entry:last-of-type { border-bottom: 0; }
.teaching-meta h3 { margin: 0 0 .35rem; font-size: 1.15rem; }
.teaching-role { font-weight: 600; margin-bottom: .15rem; }
.teaching-date { color: var(--global-text-color-light); }
.teaching-details ul { margin-bottom: 0; }
@media (max-width: 700px) { .teaching-entry { grid-template-columns: 1fr; gap: .75rem; } }
</style>

<div class="teaching-section"><h2>Higher Education</h2></div>

<div class="teaching-entry">
  <div class="teaching-meta">
    <h3>Indiana University Bloomington</h3>
    <div class="teaching-role">EDUC-W200: Teaching with Technology</div>
    <div>Associate Instructor / Instructor of Record</div>
    <div class="teaching-date">Fall 2025 · Spring 2026</div>
  </div>
  <div class="teaching-details">
    <ul>
      <li>Teaches a project-based course for pre-service teachers focused on purposeful technology integration.</li>
      <li>Supports learning around inclusion and diversity, technology for productivity, makerspaces, and technology-enhanced lesson design.</li>
      <li>Guides students in developing technology-integrated lesson plans and professional ePortfolios.</li>
    </ul>
  </div>
</div>

<div class="teaching-section"><h2>Teacher Professional Development</h2></div>

<div class="teaching-entry">
  <div class="teaching-meta">
    <h3>Binford Elementary School</h3>
    <div class="teaching-role">AI, Machine Learning &amp; Teachable Machine for Grade 5 Science Teachers</div>
    <div class="teaching-date">2026 · Bloomington, Indiana</div>
  </div>
  <div class="teaching-details">
    <ul>
      <li>Introduced foundational AI and machine-learning concepts for Grade 5 science teachers.</li>
      <li>Connected Teachable Machine with practical science-learning activities and classroom integration.</li>
    </ul>
  </div>
</div>

<div class="teaching-entry">
  <div class="teaching-meta">
    <h3>AI in Indiana</h3>
    <div class="teaching-role">Teacher Professional Development</div>
    <div class="teaching-date">2026 · Indianapolis, Indiana</div>
  </div>
  <div class="teaching-details">
    <ul>
      <li>Supported Indiana educators in exploring artificial intelligence and its classroom applications.</li>
      <li>Facilitated discussion of practical instructional uses and considerations for integrating AI in teaching.</li>
    </ul>
  </div>
</div>

<div class="teaching-entry">
  <div class="teaching-meta">
    <h3>Korea Education and Research Information Service (KERIS)</h3>
    <div class="teaching-role">ITDA Online Teaching &amp; Learning Materials · Project Lead</div>
    <div class="teaching-date">2022</div>
  </div>
  <div class="teaching-details">
    <ul>
      <li>Led teachers from six schools in developing online and blended teaching-and-learning materials for nationwide use.</li>
      <li>Used student and teacher interviews to inform material development and provided guidance for open educational resources.</li>
      <li>Delivered teacher professional development; the project was recognized as a Top 10 Team Nationwide.</li>
    </ul>
  </div>
</div>

<div class="teaching-entry">
  <div class="teaching-meta">
    <h3>Seoul Seobu District Office of Education</h3>
    <div class="teaching-role">Leading Teacher of Educational Technology</div>
    <div class="teaching-date">2023–2024 · Seoul, South Korea</div>
  </div>
  <div class="teaching-details">
    <ul>
      <li>Facilitated district-wide professional learning on generative AI and educational technology.</li>
      <li>Connected emerging technologies with practical classroom applications and pedagogically grounded integration.</li>
      <li>Delivered the 2023 invited session “Effective Classroom Integration of Generative AI.”</li>
    </ul>
  </div>
</div>

<div class="teaching-section"><h2>K–12 Teaching &amp; Instructional Innovation</h2></div>

<div class="teaching-entry">
  <div class="teaching-meta">
    <h3>Seoul Metropolitan Office of Education</h3>
    <div class="teaching-role">Tenured Public Elementary School Teacher</div>
    <div class="teaching-date">2019–2024 · Seoul, South Korea</div>
  </div>
  <div class="teaching-details">
    <ul>
      <li>Taught Grades 4 and 6 and designed localized, technology-supported curriculum and learning experiences.</li>
      <li>Developed after-school learning support for underachieving students and led AI/software learning experiences.</li>
      <li>Taught AI, computer science, and data science for gifted learners at the Integrated STEM Gifted Education Institute (2021–2024).</li>
    </ul>
  </div>
</div>

### Selected Instructional Projects

<div class="projects">
<div class="row row-cols-1 row-cols-md-3">
{% assign selected_titles = "AI-Supported Digital Mathematics Textbook|Game-Based Learning for CS Education|AI & Software Camp" | split: "|" %}
{% for project in site.projects %}
  {% if selected_titles contains project.title %}
    {% include projects.liquid %}
  {% endif %}
{% endfor %}
</div>
</div>
