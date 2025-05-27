---
title: Team
nav:
  order: 4
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

Currently, we are a team of three, along with Aarya H, a Visitin Student Program (VSP) Intern. Please reach out to us if you wish to contribute to the SQuAD projects!

{% include section.html %}

{% capture content %}

{% include figure.html image="images/1725898714944.jpg" %}
{% include figure.html image="images/IMG20250512144341.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
