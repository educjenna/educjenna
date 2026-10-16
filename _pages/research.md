---
layout: page
title: Research
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

## Publications

### Peer-Reviewed Journal Articles

1. Kwon, K., Yang, S., Kale, U., Kim, K., & **Park, J.** (2026). Generative AI in high school English career preparation units: Student interactions, perceptions, and ethical concerns. _Computers and Education: Artificial Intelligence, 10_, 100588. [https://doi.org/10.1016/j.caeai.2026.100588](https://doi.org/10.1016/j.caeai.2026.100588)

2. Kwon, K., Kale, U., Kim, K., & **Park, J.** Embodied learning for computational thinking in early elementary students: Effects of instructed vs. spontaneous approaches. (Under Review)

3. Kwon, K., **Park, J.**, Yang, S., Kale, U., & Kim, K. Generative AI for writing: Student interactions with AI feedback in a high school English classroom. (Under Review)

### Book Chapters

1. Ugur, K., Kwon, K., Ozogul, G., & **Park, J.** (2025). An inquiry-based computational thinking approach in teacher education. In _Advancing Teacher Education via Innovative Pedagogies_ (pp. 141–180). IGI Global. [https://doi.org/10.4018/979-8-3373-2660-3.ch005](https://doi.org/10.4018/979-8-3373-2660-3.ch005)

2. **Park, J.** (2023). How to design curriculum with generative AI. In _We Walk with Schools: Opening Education Communities and Future Learning_ (pp. 99–101). Seoul Seobu District Office of Education. (in Korean)

3. **Park, J.** (2022). A project to create eco-friendly buildings in a virtual reality world. In _Yes, You Can! Blended Learning Materials Collections_ (2nd ed., pp. 194–198). Seoul Metropolitan Office of Education. (in Korean)

### Peer-Reviewed Conference Proceedings

1. Kwon, K., Kim, H., Kim, K., Yang, S., & **Park, J.** (2025). AI education in English class: Exploring benefits, challenges, and ethical implications of using generative AI for argumentation. In _Proceedings of EdMedia + Innovate Learning_. AACE.

2. **Park, J.** (2023). The effects of mathematics class using virtual reality on elementary school students' spatial ability and mathematical attitudes. In _Proceedings of the 60th Conference of the Korea Society of Educational Studies in Mathematics_ (pp. 149–150).

## Presentations

### Peer-Reviewed Conference Presentations

1. **Park, J.**, & Kwon, K. (2026, November). _From efficiency to agency: Design-based research on dialogic AI-supported lesson design_. Association for Educational Communications and Technology (AECT) International Convention, Chicago, IL.

2. **Park, J.**, Kwon, K., Yang, S., Kim, K., & Kale, U. (2026, November). _Exploring AI-supported writing in high school English classrooms: Student engagement, judgment, and perceptions of AI feedback_. Association for Educational Communications and Technology (AECT) International Convention, Chicago, IL.

3. Yang, S., **Park, J.**, Park, D., Kale, U., & Kwon, K. (2026, November). _Exploring computer science project-based learning: Enacted PBL elements and teacher and student growth_. Association for Educational Communications and Technology (AECT) International Convention, Chicago, IL.

4. Yang, S., Kwon, K., Kale, U., Kim, K., & **Park, J.** (2026, November). _Learning with generative AI in high school English classes: Student interactions, perceptions, and ethical concerns in career preparation lessons_. Association for Educational Communications and Technology (AECT) International Convention, Chicago, IL.

5. Hong, S., **Park, J.**, Kwon, K., & Lim, C. (2025, October). _How artificial intelligence is integrated in education: Objectives, strategies, and outcomes—A systematic literature review_ [Poster]. Association for Educational Communications and Technology (AECT) International Convention, Las Vegas, NV.

6. **Park, J.** (2025, April). _Design principles to mitigate over-reliance in pre-service teachers' lesson design with a generative AI chatbot_. Society for Information Technology and Teacher Education (SITE), Philadelphia, PA.

7. **Park, J.** (2023, June). _The effects of mathematics class using virtual reality on elementary school students' spatial ability and mathematical attitudes_. Korea Society of Educational Studies in Mathematics, Seoul, South Korea.

### Conference Presentations

1. **Park, J.** (2026, September). _Be the bit, be the gate: How computers count and calculate_ [Poster]. Center for Research on Learning and Technology (CRLT) Graduate Student Poster Session, Bloomington, IN.

2. **Park, J.** (2025, March). _A framework for integrating computational thinking into pattern generalization in elementary mathematics education_. Instructional Systems Technology (IST) Conference, Bloomington, IN.

3. **Park, J.** (2022, October). _Developing a web-based VR instructional program for elementary mathematics_ [Poster]. SNUE Academic Festival, Seoul, South Korea.

4. **Park, J.** (2022, January). _Developing blended learning materials for overpopulated classes—integrating Korean and mathematics classes_. Presented at Seoul National University of Education, Seoul, Korea.

### Invited Talks

1. **Park, J.** (2023, July). _How to effectively make use of generative AI in my class_. Presented at the Seoul Seobu District Office of Education, Seoul, Korea.

2. **Park, J.** (2023, June; 2022, June; 2018, November; 2017, November). _How to become a successful teacher specialized in mathematics and technology in elementary school_. Presented at Jinmyeong Girls High School, Seoul, Korea.

3. **Park, J.** (2022, December). _Achievement of developing an online teaching and learning materials for ITDA_. Presented at the Korea Institute of Science and Technology Information, Jeju, Korea.
