---
layout: default
title: Participate
permalink: /participate/
noindex: true
---

# Participate

<p class="status-badge">Participant activity status: Not yet open</p>

Participant activities are not yet open. Invited participants will receive the activity link and any access instructions directly from the research team through an approved channel. The public site will not provide the real access code or study link.

This placeholder gateway may be used for general orientation and demonstration only; it is **not secure authentication**. Do not submit sensitive, classified, controlled, proprietary, or personally identifying information through this page.

<form id="access-form">
  <label for="access-code">Demo access code</label>
  <input id="access-code" name="access-code" type="text" autocomplete="off" required aria-describedby="access-help access-status">
  <p id="access-help" class="meta">Placeholder/demo only. This form does not contain a real project access code.</p>
  <button class="button" type="submit">Try placeholder gateway</button>
</form>

<p id="access-status" class="form-status" aria-live="polite"></p>
<p id="response-link" hidden><a class="button" href="#response-link-to-be-added">Placeholder response link</a></p>

<noscript><p class="site-notice">JavaScript is needed only for this access-code gateway. Please contact the project team for the activity link.</p></noscript>

If you have trouble accessing the response activity, please contact the project team.

<script>
  (function () {
    var form = document.getElementById('access-form');
    var input = document.getElementById('access-code');
    var status = document.getElementById('access-status');
    var link = document.getElementById('response-link');

    form.addEventListener('submit', function (event) {
      event.preventDefault();
      if (input.value.trim() === 'REPLACE_WITH_PROJECT_CODE') {
        status.textContent = 'Placeholder accepted. In a real activity, instructions are distributed directly by the research team.';
        link.hidden = false;
      } else {
        status.textContent = 'That code was not recognized. Check your invitation or contact the project team.';
        link.hidden = true;
      }
    });
  }());
</script>
