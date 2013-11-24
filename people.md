---
layout: frontpage
title: People
---

# Faculty

-----

<ul>
{% for person in site.data.people %}
{% if person.role == "faculty" %}
<li>**{{ person.name }}** - {{ person.description }}</li>
{% else %}
{% endif %}
{% endfor %}
</ul>

# Students

-----

<ul>
{% for person in site.data.people %}
{% if person.role == "student" %}
<li>**{{ person.name }}** - {{ person.description }}</li>
{% else %}
{% endif %}
{% endfor %}
</ul>

-----

# Alumni

-----

SLDG (University of Kansas) and KBSE (University of
Cincinnati) students who have graduated under my supervision. 

## PhD Graduates

-----

{% for person in site.data.people %}
{% if person.role == "phd" %}
* **{{ person.name }}** - {{ person.description }}
{% else %}
{% endif %}
{% endfor %}

## MS Graduates

-----

{% for person in site.data.people %}
  {% if person.role == "ms" %}
* **{{ person.name }}** - {{ person.description }}
  {% else %}
  {% endif %}
{% endfor %}

## Undergraduates

-----

{% for person in site.data.people %}
  {% if person.role == "ug" %}
* **{{ person.name }}** - {{ person.description }}
  {% else %}
  {% endif %}
{% endfor %}
