---
layout: default
title: Materials
permalink: /materials/
---

# Project materials

Selected, approved materials will be made available here in accessible, downloadable formats. Placeholder entries indicate planned resources; files marked “Coming soon” are not yet published.

<div class="card-grid">
  {% for item in site.data.downloads %}
    {% include download_card.html item=item %}
  {% endfor %}
</div>
