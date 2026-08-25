---
permalink: /
title: "Zhaozhou Tang"
excerpt: "Zhaozhou Tang's academic portfolio"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

Hello! I am Zhaozhou Tang, a Ph.D. student at Georgia Tech. I work in the [CPSec lab](https://sites.gatech.edu/capcpsec/), advised by Prof. [Saman Zonouz](https://sites.google.com/site/samanzonouz4n6/saman-zonouz) and Dr. [Khaled Serag](https://khaled-alsharif.github.io/). My research investigates the security of cyber-physical systems with a focus on automotive systems.

Education
======
- Ph.D. in Electrical and Computer Engineering, Georgia Tech, 2023-Present
- B.S. in Electrical Engineering, Georgia Tech, 2019-2023

Publications
======
{% assign pubs = site.publications | sort: 'order' %}
{% for post in pubs %}
<p style="margin: 0 0 1.2em 0;">
  <strong>{{ post.title }}</strong>{% if post.paperurl %} [<a href="{{ post.paperurl }}">pdf</a>]{% endif %}<br>
  {{ post.authors }}<br>
  {{ post.venue }}
  {% if post.award %}<br><span style="color: #1a7f37;">{{ post.award }}</span>{% endif %}
</p>
{% endfor %}

Teaching
======
- **Graduate Teaching Assistant**: Measurements, Circuits and Microelectronics Laboratory, Georgia Tech, Spring 2023

Service
======
- **Program Committee**, USENIX Security 2027
