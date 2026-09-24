---
layout: default
title: Materials
permalink: /materials/
---

# Project materials

Approved public materials are available below. Participant-specific activity materials will be distributed directly to invited participants through an approved channel and are listed here without public links.

## Public materials

These files are approved for access from the public project site.

<div class="card-grid download-grid">
  {% assign public_downloads = site.data.downloads | where: "access", "Public" %}
  {% for item in public_downloads %}
    {% include download_card.html item=item %}
  {% endfor %}
</div>

## Invitation-only materials

These materials are listed for orientation only. They do not have public download links and will be provided directly if they are needed for an invited activity.

<div class="card-grid download-grid">
  {% assign invitation_downloads = site.data.downloads | where: "access", "Direct distribution only" %}
  {% for item in invitation_downloads %}
    {% include download_card.html item=item %}
  {% endfor %}
</div>

## Internal materials not posted publicly

Internal planning, working, participant-management, and analysis materials are not posted on this public site. A reference on this page does not indicate that a private file is publicly available.
