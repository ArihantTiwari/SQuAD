---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

Have questions about the SQuAD projects or are interested in collaborating? We'd love to hear from you! Please drop by at the details below or feel free to contact any of the team members!

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

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Lorem ipsum"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}
{% endcapture %}

{% capture col2 %}
Indian Institute of Astrophysics/
Bengaluru, Karnataka, India
{% endcapture %}

{% capture col3 %}
{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}
