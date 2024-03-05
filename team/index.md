---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Courtot lab is located at the Ontario Institute for Cancer Research. It is the research arm of the Genome Informatics program, which also encompasses the OICR software engineering team, led by Dr. Courtot. At any time the software engineering team has around 25 staff members, including bioinformaticians, devops, software developers, UI/UX and others. We value diversity, inclusivity and transparency.



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}



