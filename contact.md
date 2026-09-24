---
layout: default
title: Contact
permalink: /contact/
---

# Contact the project team

{% include site_notice.html title="Contact routing in preparation" text="Project contact routing is being finalized. For now, collaborators should use the contact channel provided directly by the research team." %}

The form below is a visible placeholder for collaborator review. Its endpoint has not been configured, so it should not be used to send a message.

**Do not submit classified, controlled, proprietary, sensitive, or personally identifying information through this form.**

<form action="https://formspree.io/f/REPLACE_WITH_FORM_ID" method="post">
  <label for="contact-name">Name</label>
  <input id="contact-name" name="name" type="text" autocomplete="name" disabled>

  <label for="contact-email">Email</label>
  <input id="contact-email" name="email" type="email" autocomplete="email" disabled>

  <label for="contact-message">Message</label>
  <textarea id="contact-message" name="message" rows="7" disabled></textarea>

  <button class="button" type="submit" disabled>Form not yet available</button>
</form>
