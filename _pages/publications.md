---
layout: page
permalink: /publications/
title: publications
description:
profile:
  align: right
  image: Sevgi_WiP.png
  image_circular: false
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="type">

**Journal Articles**

{% bibliography --query @article --sort_by year --order descending %}

<hr>

**Book Chapters**

{% bibliography --query @incollection --sort_by year --order descending %}

<hr>

**Conference Proceedings**

{% bibliography --query @inproceedings --sort_by year --order descending %}

<hr>

**Manuscripts**

{% bibliography --query @unpublished --sort_by year --order descending %}
</div>
