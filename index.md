---
layout: frontpage
title: SLDG
---

The System Level Design Group is comprised of students and faculty
investigating all aspects of systems level design at The University of
Kansas Information and Telecommunications Technology Center. Advised
by Dr. Perry Alexander, the group is engaged in several research
projects including specification, verification and synthesis of
complex systems, trusted computing, and system-level design. Each
applies engineering methods and formal modeling to specific systems
engineering activities. The System Level Design group is supported by
The University of Kansas' Information and Telecommunication Technology
Center's Computer Systems Design Laboratory. 

# Recent Activities

-----

* "Verifying TPM Protocols Using a State Monad" submitted to FM'14
* Dr. Perry Alexander named Outstanding Honors Advisor by the KU
  Honors Program for 2013
* "Synthesizing Software Infrastructure for Remote Attestation"
  submitted with Andy Gill and Prasad Kulkarning to the NSF SaTC
  program
* ArmoredSoftware awarded by the United States Department of Defense
* ACHILLES awarded with Adventium Labs by DARPA

# Team

-----

SLDG is a part of The Information and Telecommunication
Technology Center at The University of Kansas.

## Faculty

{% for person in site.data.people %}
{% if person.role == "faculty" %}
* {{ person.name }}
{% else %}
{% endif %}
{% endfor %}

## Students

<ul>
{% for person in site.data.people %}
{% if person.role == "student" %}
<li>{{ person.name }}</li>
{% else %}
{% endif %}
{% endfor %}
</ul>

# Weekly Research Meetings

-----

* ArmoredSoftware - 10am Tuesday - 208 Nichols
* Lambda - TBD
