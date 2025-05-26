---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

There are three projects under SQuAD as of May 2025. We have used UV spectra to find anomalous QSOs and study variablity trends. Optical spectra has been utilized to find anomalous NLSy1 galaxies. All spectra so far have been obtained from the Sloan Digital Sky Survey Data Release 16 [(SDSS DR16)](https://skyserver.sdss.org/dr16/en/home.aspx).

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
