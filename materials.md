---
layout: default
title: Materials
permalink: /materials/
---

# Project materials

Approved public project materials will be posted here in accessible, downloadable formats when they are available. Some project materials are distributed directly to invited participants and are listed without public download links.

Internal planning materials are not posted publicly. Private participant materials are not hosted on this public site unless they have been explicitly approved for public release.

<div class="card-grid">
  {% for item in site.data.downloads %}
    {% include download_card.html item=item %}
  {% endfor %}
</div>
