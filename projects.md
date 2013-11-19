---
layout: frontpage
title: Projects
---

# Verified TPM

-----

* [TPM Verification](http://palexand.github.io/verified-tpm12)

# ArmoredSoftware

-----

* [ArmoredSoftware](http://armoredsoftware.github.io/ArmoredSoftware)

# ACHILLES

-----

* Website coming soon

{% for project in site.data.projects %}

# {{ project.name }}

---

* [{{ project.name }}](http://{{ project.github }}.github.io/{{ project.repo }})

{% endfor %}
