---
layout: default
title: Participate
permalink: /participate/
---

# Participate

Invited participants should use the access code provided by the research team. This gateway is a low-friction routing mechanism only; it is **not secure authentication** and should not be used to submit sensitive information.

<form id="access-form">
  <label for="access-code">Access code</label>
  <input id="access-code" name="access-code" type="text" autocomplete="off" required aria-describedby="access-help access-status">
  <p id="access-help" class="meta">Enter the code exactly as it appears in your invitation.</p>
  <button class="button" type="submit">Continue to response activity</button>
</form>

<p id="access-status" class="form-status" aria-live="polite"></p>
<p id="response-link" hidden><a class="button" href="#response-link-to-be-added">Open the response activity</a></p>

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
        status.textContent = 'Code accepted. Use the link below to continue.';
        link.hidden = false;
      } else {
        status.textContent = 'That code was not recognized. Check your invitation or contact the project team.';
        link.hidden = true;
      }
    });
  }());
</script>
