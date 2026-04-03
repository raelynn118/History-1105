---
title: HIST 1105 Spring 2026
layout: base
date: 2025-10-21
header-image: "/assets/images/Welcome ot New Mexico imag.jpeg"
header-title: Making New Mexico History
header-subtitle: Student Final Projects
header-position: 35% center
---

# The Asian American and Pacific Islander Experience in New Mexico 

Asian American and Pacific Islanders have contributed to United States history from as early as the 17th century.  HIST 1105 Making History: The Asian American and Pacific Islander Experience  invited students to explore how AAPI experiences are the result of changing global relations, the development of the United States as a nation, and subsequent U.S. relations with Asian and Pacific Island nations and diasporic commmunities. At the same time, students learned about historical interpretation and the choices historians make in documenting U.S. history. The final projects on this website reflect students' own research in New Mexico newspapers about AAPI experiences, the questions they asked, and the answers they found. Students also learned how to build their own webpages based on the resources provided by Jonathan Seyfried and the Amaranth Lab. The final projects here reflect the process of learning what it means to think and write historically.

{% assign all_pages = site.pages %}
{% assign cards = all_pages | where_exp: "p", "p.path contains 'essays/'" | where_exp: "p", "p.path != 'essays/index.md'" %}

{% include nav/card-grid.html cards=cards %}

