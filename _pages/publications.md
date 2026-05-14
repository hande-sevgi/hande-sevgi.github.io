---
layout: page
permalink: /publications/
title: publications
description:
nav: true
nav_order: 2
---

{% include bib_search.liquid %}

{% bibliography --sort_by year --order descending %}
