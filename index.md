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

<ul id="archive">
{% for post in site.posts %}
  <li class="post-{{ post.category }}">
  {% if post.external_url == nil %}
    <a href="{{ post.url }}">{{ post.title }}</a><abbr>{{ post.date | date_to_string }}</abbr>
  {% else %}
    <a href="{{ post.external_url }}">{{ post.title }}</a><abbr>{{ post.date | date_to_string }}</abbr>
  {% endif %}
  </li>
{% endfor %}
</ul>

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

<ul>
{% for person in site.data.people %}
{% if person.role == "faculty" %}
  {% if person.web == nil %}
<li>{{ person.name }}</li>
  {% else %}
<li><a href="{{ person.web }}">{{ person.name }}</a></li>
  {% endif %}
{% else %}
{% endif %}
{% endfor %}
</ul>

## Students

<ul>
{% for person in site.data.people %}
{% if person.role == "student" %}
  {% if person.web == nil %}
<li>{{ person.name }}</li>
  {% else %}
<li><a href="{{ person.web }}">{{ person.name }}</a></li>
  {% endif %}
{% else %}
{% endif %}
{% endfor %}
</ul>

# Weekly Research Meetings

-----

<ul>
{% for meeting in site.data.meetings %}
<li>{{ meeting.name }} - {{ meeting.time }} - {{ meeting.place }}</li>
{% endfor %}
</ul>

