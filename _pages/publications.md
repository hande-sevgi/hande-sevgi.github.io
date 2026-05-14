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

<hr>

**Journal Articles**

{% bibliography --query @*[type=journals] --sort_by year --order descending %}


<hr>

**Book Chapters**
{% bibliography --query @*[type=bookchapters] --sort_by year --order descending %}


<hr>
**Conference Proceedings**

{% bibliography --query @*[type=proceedings] --sort_by year --order descending %}


<hr>

**Manuscripts/Work in Progress**

{% bibliography --query @*[type=manuscripts] --sort_by year --order descending %}

</div>
