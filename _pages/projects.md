---
layout: about
title: projects
permalink: /projects/
description:
nav: true
nav_order: 3
display_categories: [research, in progress, random ideas]
horizontal: false
---

{% if site.enable_project_categories and page.display_categories %} {% for category in page.display_categories %}
{{ category }}
{% assign categorized_projects = site.projects | where: "category", category %} {% assign sorted_projects = categorized_projects | sort: "importance" %} {% if page.horizontal %}
{% for project in sorted_projects %} {% include projects_horizontal.liquid %} {% endfor %}
{% else %}
{% for project in sorted_projects %} {% include projects.liquid %} {% endfor %}
{% endif %} {% endfor %}
{% else %}

{% assign sorted_projects = site.projects | sort: "importance" %}

{% if page.horizontal %}

{% for project in sorted_projects %} {% include projects_horizontal.liquid %} {% endfor %}
{% else %}
{% for project in sorted_projects %} {% include projects.liquid %} {% endfor %}
{% endif %} {% endif %}
