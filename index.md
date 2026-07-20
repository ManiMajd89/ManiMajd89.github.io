---
layout: default
title: Home
---
<link rel="stylesheet" href="{{ '/style.css' | relative_url }}">

{% include navigation.html %}

<section class="home-hero">
  <img class="profile-pic" src="{{ '/175567155.jpeg' | relative_url }}" alt="Portrait of Mani Majd">
  <div class="home-intro">
    <p class="eyebrow">Engineering Science · University of Toronto</p>
    <h1>Mani Majd</h1>
    <p class="lead">
      I am an engineering student interested in robotics, machine learning, and
      computational modeling. I enjoy turning technical ideas into practical,
      understandable systems.
    </p>
    <div class="hero-actions">
      <a class="button button-primary" href="{{ '/projects' | relative_url }}">Explore my projects</a>
      <a class="button button-secondary" href="{{ '/portfolio' | relative_url }}">View my resume</a>
    </div>
  </div>
</section>

<section class="home-details" aria-label="Background and interests">
  <article class="detail-block">
    <p class="section-kicker">Education</p>
    <h2>Engineering Science</h2>
    <p>
      Bachelor of Applied Science at the University of Toronto, with work spanning
      software, applied mathematics, intelligent systems, and engineering design.
    </p>
    <p class="detail-note">Toronto, Canada</p>
  </article>

  <article class="detail-block">
    <p class="section-kicker">Beyond coursework</p>
    <h2>Curious by default</h2>
    <p>
      Outside technical projects, I enjoy cooking, solving puzzles, and leading
      STEM initiatives. Those interests keep me practical, collaborative, and open
      to different ways of approaching a problem.
    </p>
  </article>
</section>
