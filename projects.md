---
layout: frontpage
title: Projects
---

# Active Projects

{% for project in site.data.projects %}

## {{ project.name }}

-----

{% if project.ghpages %}
[{{ project.name }}](http://{{ project.github }}.github.io/{{ project.repo }}) - {{ project.description }}
{% else %}
[{{ project.name }}](https://github.com/{{ project.github }}/{{ project.repo }}) - {{ project.description }}
{% endif %}

Sponsors: {{ project.sponsor }}

{% endfor %}

# Inactive Projects

{% for project in site.data.inactive-projects %}

## {{ project.name }}

-----

{% if project.ghpages %}
[{{ project.name }}](http://{{ project.github }}.github.io/{{ project.repo }}) - {{ project.description }}
{% else %}
[{{ project.name }}](https://github.com/{{ project.github }}/{{ project.repo }}) - {{ project.description }}
{% endif %}

Sponsors: {{ project.sponsor }}

{% endfor %}

