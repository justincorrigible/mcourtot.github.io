---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Courtot lab is located at the Ontario Institute for Cancer Research. It is the research arm of the Genome Informatics program, which also encompasses the OICR software engineering team, led by Dr. Courtot. At any time the software engineering team has around 25 staff members, including bioinformaticians, devops, software developers, UI/UX and others. We value diversity, inclusivity and transparency.



{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: progmanager" %}
{% include list.html data="members" component="portrait" filters="role: programmer" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: admin" %}

{% include section.html dark=true %}

We are always interested in new ideas and opportuntities. Students must be accepted in a graduate program at the University of Toronto in the [Department of Medical Biophysics](https://medbio.utoronto.ca/) (PhD or MSc programs).
{%
  include button.html
  icon="fa-solid fa-handshake-angle"
  text="Join the Team"
  link="contact"
  style="button"
%}



{% include section.html %}


{% include list.html data="members" component="portrait" filters="role: mascot" style="small" %}