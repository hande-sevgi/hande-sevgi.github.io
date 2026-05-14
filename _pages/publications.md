---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="type">


{% bibliography --query @article --sort_by year --order descending %}

<hr>

{% bibliography --query @incollection --sort_by year --order descending %}

<hr>

{% bibliography --query @inproceedings --sort_by year --order descending %}

<hr>

{% bibliography --query @phdthesis --sort_by year --order descending %}
{% bibliography --query @mastersthesis --sort_by year --order descending %}
{% bibliography --query @unpublished --sort_by year --order descending %}

</div>
