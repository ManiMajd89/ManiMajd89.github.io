---
layout: default
title: Portfolio
---
<link rel="stylesheet" href="{{ '/style.css' | relative_url }}">

{% include navigation.html %}

<section class="page-hero">
  <p class="eyebrow">Experience · education · technical work</p>
  <h1>Resume</h1>
  <p class="lead">
    A focused record of my education, research experience, and engineering work in
    robotics, machine learning, and AI.
  </p>
</section>

<section class="resume-section">
  <div class="section-heading">
    <div>
      <p class="section-kicker">Current document</p>
      <h2>Mani Majd · Resume</h2>
    </div>
    <a class="button button-primary" href="{{ '/Mani_Majd_AuToronto.pdf' | relative_url }}">Open PDF</a>
  </div>

  <iframe
    class="resume-frame"
    src="{{ '/Mani_Majd_AuToronto.pdf' | relative_url }}#view=FitH"
    title="Mani Majd resume preview"
    loading="lazy">
  </iframe>
</section>
