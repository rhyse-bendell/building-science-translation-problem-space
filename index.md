---
layout: default
title: Home
permalink: /
---

<section class="hero hero-home">
  <div class="hero-inner">
    <p class="section-label">Army Research Office-funded project</p>
    <h1>Building a Problem Space for Science Translation</h1>
    <p class="subtitle">Team Science and the Translation of Research Findings for Application in the Real World</p>
    <p class="hero-summary">This project examines how scientific findings move from research settings into real-world use. It will build a structured problem space by identifying the actors, contexts, barriers, facilitators, and leverage points that shape whether research becomes usable policy, programs, technologies, practices, or capabilities.</p>
    <nav class="hero-actions" aria-label="Project links">
      <a class="button button-light" href="{{ '/about/' | relative_url }}">Learn about the project</a>
      <a class="button button-outline" href="{{ '/method/' | relative_url }}">View the method</a>
      <a class="text-link" href="{{ '/participate/' | relative_url }}">Participation status <span aria-hidden="true">→</span></a>
    </nav>
  </div>
</section>

<section class="content-section intro-section" aria-labelledby="brief-heading">
  <div class="two-column two-column-wide">
    <div>
      <p class="section-label">Project in brief</p>
      <h2 id="brief-heading">Understanding the path from research to use</h2>
    </div>
    <div class="prose-block">
      <p>Scientific knowledge moves toward application through a complex ecosystem of people, organizations, decisions, and constraints. This project brings together perspectives from defense, industry, academia, and adjacent communities to examine that ecosystem.</p>
      <p>The aim is to develop a structured representation of science translation: one that makes the relevant actors and contexts visible while clarifying the barriers, facilitators, leverage points, and coordination needs that influence progress from research to real-world use.</p>
    </div>
  </div>
</section>

<section class="section-band" aria-labelledby="products-heading">
  <div class="section-inner">
    <p class="section-label">Expected products</p>
    <h2 id="products-heading">What the project will produce</h2>
    <p class="section-intro">The project is designed to create practical, stakeholder-informed resources for understanding and improving science translation.</p>
    <div class="card-grid product-grid">
      <article class="card accent-card"><h3>Science translation problem map</h3><p>A structured map of major barriers, facilitators, stakeholder roles, contextual factors, and coordination needs that shape research translation.</p></article>
      <article class="card accent-card"><h3>Stakeholder-informed framework</h3><p>A framework showing how translation processes vary across defense, academia, industry, and adjacent communities, and where coordination can be improved.</p></article>
      <article class="card accent-card"><h3>Priority areas and leverage points</h3><p>Identification of problems, relationships, and intervention points stakeholders view as important, feasible, and actionable.</p></article>
      <article class="card accent-card"><h3>Briefings, reports, and scholarly products</h3><p>Outputs to support future research, program planning, stakeholder coordination, and practical improvements in moving findings toward use.</p></article>
    </div>
  </div>
</section>

<section class="content-section" aria-labelledby="process-heading">
  <p class="section-label">Approach</p>
  <h2 id="process-heading">How the project works</h2>
  <p class="section-intro">Group Concept Mapping provides a structured path from stakeholder experience to interpretable maps, themes, and priorities.</p>
  <ol class="process-band process-band-home">
    <li><strong>Engage stakeholders</strong><span>Bring together relevant perspectives.</span></li>
    <li><strong>Generate statements</strong><span>Gather examples and observations.</span></li>
    <li><strong>Sort and rate concepts</strong><span>Organize and assess the statements.</span></li>
    <li><strong>Map the problem space</strong><span>Analyze patterns and relationships.</span></li>
    <li><strong>Interpret and apply results</strong><span>Identify meaning and practical value.</span></li>
  </ol>
</section>

<section class="section-band section-band-dark" aria-labelledby="engagement-heading">
  <div class="section-inner">
    <p class="section-label">Defense · Industry · Academia</p>
    <h2 id="engagement-heading">Engagement structure</h2>
    <p class="section-intro">Participant engagement is organized through three complementary groups, each contributing at a different level.</p>
    <div class="card-grid engagement-grid">
      <article class="card"><h3>Advisory Group</h3><p>Provides high-level guidance on direction, scope, stakeholder perspectives, interpretation, and practical relevance.</p></article>
      <article class="card"><h3>Core Group</h3><p>Contributes examples, reviews materials, organizes and rates concepts, and helps interpret the results.</p></article>
      <article class="card"><h3>Extended Group</h3><p>Broadens stakeholder input through invited activities during selected phases of the project.</p></article>
    </div>
  </div>
</section>

<section class="content-section" aria-labelledby="phase-heading">
  <aside class="status-callout">
    <div><p class="status-badge">Current phase</p><h2 id="phase-heading">Preparing for participant engagement</h2></div>
    <p>The project team is currently preparing materials and identifying candidates for Core Group and Extended Group participation. Participant activities are not yet open through the public site.</p>
    <a class="text-link" href="{{ '/participate/' | relative_url }}">View participation status <span aria-hidden="true">→</span></a>
  </aside>
</section>

<section class="section-band" aria-labelledby="materials-heading">
  <div class="section-inner">
    <div class="section-heading-row">
      <div><p class="section-label">Resources</p><h2 id="materials-heading">Public materials</h2></div>
      <p>Project overview documents provide additional detail about the project and its engagement groups.</p>
    </div>
    <div class="card-grid download-grid public-materials">
      {% assign public_downloads = site.data.downloads | where: "access", "Public" %}
      {% for item in public_downloads %}{% include download_card.html item=item %}{% endfor %}
    </div>
  </div>
</section>
