---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Have questions or are interested in collaborating? We'd love to hear from you!

{%
  include button.html
  type="email"
  text="vivek.m@iiap.res.in"
  link="vivek.m@iiap.res.in"
%}
{%
  include button.html
  type="phone"
  text="(+91) 7738985547"
  link="+917738985547"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/vNN46QuFRYYjxJnB9"
%}

{% include section.html dark=true %}

{% capture col1 %}
Indian Institute of Astrophysics\
Bengaluru, Karnataka, India

{% include cols.html col1=col1 %}
