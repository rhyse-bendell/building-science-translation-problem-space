---
layout: default
title: About
permalink: /about/
---

<header class="page-hero">
  <p class="section-label">About the project</p>
  <h1>Mapping how science moves toward real-world use</h1>
  <p class="lead">This Army Research Office-funded project is building a structured, stakeholder-informed account of the science translation ecosystem.</p>
</header>

<section class="content-section" aria-labelledby="overview-heading">
  <div class="two-column two-column-wide">
    <div><p class="section-label">Overview</p><h2 id="overview-heading">A clearer view of science translation</h2></div>
    <div class="prose-block">
      <p><strong>Building a Problem Space for Science Translation</strong> examines how scientific findings move from research settings into real-world use. Research may ultimately inform policy, programs, technologies, practices, or capabilities, but the path from discovery to application is rarely direct.</p>
      <p>The project will identify the actors, contexts, barriers, facilitators, leverage points, and coordination needs that shape that path. The resulting problem space is intended to offer a clear and usable representation of the people, processes, relationships, and decision points involved.</p>
    </div>
  </div>
</section>

<section class="section-band" aria-labelledby="why-heading">
  <div class="section-inner two-column">
    <div><p class="section-label">Project rationale</p><h2 id="why-heading">Why science translation is being mapped</h2></div>
    <div class="prose-block"><p>Science translation crosses organizational and professional boundaries. Different communities may use different language, work within different constraints, or define useful evidence and successful application differently.</p><p>Bringing practical experience from across the research-to-use pathway into a shared structure can reveal where processes vary, where coordination breaks down, and where focused improvements may be both feasible and valuable.</p></div>
  </div>
</section>

<section class="content-section" aria-labelledby="about-products-heading">
  <p class="section-label">Expected products</p><h2 id="about-products-heading">From stakeholder perspectives to useful resources</h2>
  <div class="card-grid product-grid">
    <article class="card accent-card"><h3>Science translation problem map</h3><p>A structured map of major barriers, facilitators, stakeholder roles, contextual factors, and coordination needs that shape research translation.</p></article>
    <article class="card accent-card"><h3>Stakeholder-informed framework</h3><p>A framework showing how translation varies across defense, academia, industry, and adjacent communities, including where coordination can be improved.</p></article>
    <article class="card accent-card"><h3>Priority areas and leverage points</h3><p>Problems, relationships, and intervention points that stakeholders view as important, feasible, and actionable.</p></article>
    <article class="card accent-card"><h3>Briefings, reports, and scholarly products</h3><p>Outputs intended to support future research, program planning, stakeholder coordination, and practical improvements in moving findings toward use.</p></article>
  </div>
</section>

<section class="section-band section-band-dark" aria-labelledby="model-heading">
  <div class="section-inner">
    <p class="section-label">Engagement model</p><h2 id="model-heading">Multiple perspectives, complementary roles</h2>
    <p class="section-intro">The project is structured around defense, industry, and academia, with engagement occurring through three groups.</p>
    <div class="card-grid engagement-grid">
      <article class="card"><h3>Advisory Group</h3><p>Provides high-level guidance so the project is framed clearly, includes the right perspectives, uses appropriate language, and produces credible and useful outputs. Members advise on direction, scope, recruitment, interpretation, and practical relevance rather than completing detailed Core Group activities.</p></article>
      <article class="card"><h3>Core Group</h3><p>Helps develop a clear and usable description of science translation by contributing examples, reviewing materials, organizing and rating concepts, and interpreting results. Members do not manage the project, conduct the analysis, or write the final report.</p></article>
      <article class="card"><h3>Extended Group</h3><p>Provides broader stakeholder input through invited activities. Members may contribute examples, sort statements into meaningful groups, rate them on key dimensions, or offer feedback during selected phases.</p></article>
    </div>
  </div>
</section>

<section class="content-section people-section" aria-labelledby="team-heading">
  <div class="two-column">
    <div><p class="section-label">People</p><h2 id="team-heading">Research team</h2></div>
    <ul class="people-list">
      <li><strong>Stephen M. Fiore</strong><span>University of Central Florida</span></li>
      <li><strong>Rhyse Bendell</strong><span>University of Central Florida</span></li>
      <li><strong>Scott Rosas</strong><span>Concept Systems Inc.</span></li>
      <li><strong>Greg Ruark</strong><span>Army Research Office</span></li>
    </ul>
  </div>
</section>

<section class="section-band" aria-labelledby="advisory-heading">
  <div class="section-inner two-column">
    <div><p class="section-label">Project guidance</p><h2 id="advisory-heading">Advisory group</h2><p>The Advisory Group brings high-level guidance and a range of perspectives to the project.</p></div>
    <ul class="name-list name-panel"><li>Matthew Brashears</li><li>Joseph Cohn</li><li>Ryan Kilgore</li><li>Peter Kooshabehadeh</li><li>Michele Masucci</li><li>David Montgomery</li><li>Jason Owen-Smith</li><li>James Pharmer</li><li>Daniel Serfaty</li><li>Scott Tannenbaum</li></ul>
  </div>
</section>

<section class="content-section" aria-labelledby="about-materials-heading">
  <p class="section-label">Resources</p><h2 id="about-materials-heading">Public materials</h2>
  <p class="section-intro">These public documents provide more detail about the project and selected engagement roles.</p>
  <div class="card-grid download-grid public-materials">
    {% assign public_downloads = site.data.downloads | where: "access", "Public" %}
    {% for item in public_downloads %}{% include download_card.html item=item %}{% endfor %}
  </div>
</section>
