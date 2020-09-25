---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
The objective of this page is to be used as a place to present myself and to provide useful information about my skills and working area.
I have been working with software development since 2004. My areas of expertise vary from software testing to Frontend, Backend (full stack) development and large scale batch processing.

Besides programming, I have been teaching at a private University in the Northeast region of Brazil the courses of Computer Algorithms, Foundations of Software Engineering and Information Systems.

:brazil:

Olá eu sou **{{ site.author.name }}** :wave:,<br>
O objetivo desta página é o de ser utilizada como um local para me apresentar e prover informações úteis acerca de minhas habilidades e área de trabalho.
Tenho trabalhado com desenvolvimento de software desde 2004. Minhas áreas de conhecimento variam desde testes de software passando por desenvolvimento Back e Frontend (fukll stack) chegando até a sistemas de processamento em batch de larga escala.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
