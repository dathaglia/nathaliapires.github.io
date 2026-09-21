---
layout: page
permalink: /publications/
title: Publications
description: 
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

<div class="publications">

<h2>Articles</h2>
{% bibliography --query @article %}

<h2>Proceedings</h2>
{% bibliography --query @inproceedings %}

<h2>Books and Chapters</h2>
{% bibliography --query @book %}
{% bibliography --query @incollection %}

</div>
