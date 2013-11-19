---
layout: frontpage
title: Projects
---

# Active Projects

{% for project in site.data.projects %}

<p>
## {{ project.name }}

-----

[{{ project.name }}](http://{{ project.github }}.github.io/{{ project.repo }}) - {{ project.description }}
Sponsors: {{ project.sponsor }}
</p>

{% endfor %}
