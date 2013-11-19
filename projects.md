---
layout: frontpage
title: Projects
---

{% for project in site.data.projects %}

# {{ project.name }}

---

* [{{ project.name }}](http://{{ project.github }}.github.io/{{ project.repo }})

{% endfor %}
