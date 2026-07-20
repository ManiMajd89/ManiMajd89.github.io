---
layout: default
title: Home
---
<link rel="stylesheet" href="{{ '/style.css' | relative_url }}">

{% include navigation.html %}

<section class="home-hero">
  <img class="profile-pic" src="{{ '/175567155.jpeg' | relative_url }}" alt="Portrait of Mani Majd">
  <div class="home-intro">
    <p class="eyebrow">Engineering Science · Robotics + AI</p>
    <h1>Mani Majd</h1>
    <p class="lead">
      I study Engineering Science at the University of Toronto, specializing in
      Robotics and pursuing an AI minor. My work focuses on robot learning,
      computer vision, and neuromorphic AI, from imitation-learning systems for
      robotic manipulation to perception models for autonomous platforms.
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
    <h2>Engineering Science</h2>
    <p>
      I am completing a B.A.Sc. in Engineering Science through the Robotics
      Specialist program, alongside an AI minor and PEY Co-op. The program combines
      foundations in algorithms, computer systems, probability, and applied
      mathematics with advanced work in intelligent systems.
    </p>
    <p class="detail-note">Robotics Specialist · AI Minor · PEY Co-op</p>
  </article>

  <article class="detail-block">
    <p class="section-kicker">Research</p>
    <h2>Robot learning and perception</h2>
    <p>
      My research focuses on learning-based perception and decision-making for
      autonomous systems. At the Technical University of Munich, I work on
      imitation learning for robotic manipulation and temporal reasoning for
      semantic object search. Previously, at York University's LCRAIN Lab, I
      developed spiking neural networks for efficient visual perception.
    </p>
  </article>
</section>
