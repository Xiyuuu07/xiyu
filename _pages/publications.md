---
layout: page
permalink: /publications/
title: publications
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<div class="publications">

<h2 style="color: #A2B9C3; font-weight: bold; margin-top: 2rem; margin-bottom: 1rem;">Journal Articles</h2>

{% bibliography -f papers -q @article %}

<h2 style="color: #A2B9C3; font-weight: bold; margin-top: 2rem; margin-bottom: 1rem;">Conference Presentations</h2>

{% bibliography -f papers -q @inproceedings %}

</div>
