---
layout: default
title: Home
---
<link rel="stylesheet" href="{{ '/style.css' | relative_url }}">

{% include navigation.html %}

<section class="home-hero">
  <img class="profile-pic" src="{{ '/175567155.jpeg' | relative_url }}" alt="Portrait of Mani Majd">
  <div class="home-intro">
    <p class="eyebrow">Third-year Engineering Science · Robotics + AI</p>
    <h1>Mani Majd</h1>
    <p class="lead">
      I am a third-year Engineering Science student at the University of Toronto,
      specializing in Robotics and pursuing an AI minor. I build learning systems
      for robotics and computer vision, with current work in imitation learning,
      semantic object search, and neuromorphic AI.
    </p>
    <div class="hero-actions">
      <a class="button button-primary" href="{{ '/projects' | relative_url }}">Explore my projects</a>
      <a class="button button-secondary" href="{{ '/portfolio' | relative_url }}">View my resume</a>
    </div>
  </div>
</section>

<section class="home-details" aria-label="Education and research experience">
  <article class="detail-block">
    <p class="section-kicker">Education</p>
    <h2>Robotics + AI</h2>
    <p>
      I am completing a B.A.Sc. in Engineering Science with a Robotics
      specialization, an AI minor, and PEY Co-op. My coursework spans algorithms,
      computer systems, probability, linear algebra, and applied mathematics.
    </p>
    <p class="detail-note">3.91 cumulative GPA · Dean's Honours List ×4 · Class of 2029</p>
  </article>

  <article class="detail-block">
    <p class="section-kicker">Research &amp; leadership</p>
    <h2>Learning systems in practice</h2>
    <p>
      My research at TUM's Learning Systems and Robotics Lab and York University's
      LCRAIN Lab spans robot learning, semantic search, and neuromorphic vision. I
      also lead OCT-EyeSNN at UTMIST, contribute to autonomous perception at UTFR,
      and previously worked on rover perception with UTRA.
    </p>
  </article>
</section>
