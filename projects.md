---
layout: default
title: Projects
---
<link rel="stylesheet" href="style.css">

<nav>
  <ul style="list-style-type: none; padding: 0; display: flex; gap: 1rem; background-color: #f8f9fa; padding: 10px; border-bottom: 2px solid #ddd;">
    <li><a href="/" style="text-decoration: none; font-weight: bold;">Home</a></li>
    <li><a href="/portfolio" style="text-decoration: none; font-weight: bold;">Portfolio</a></li>
    <li><a href="/projects" style="text-decoration: none; font-weight: bold;">Projects</a></li>
    <li><a href="/contact" style="text-decoration: none; font-weight: bold;">Contact</a></li>
  </ul>
</nav>

<section class="page-hero">
  <p class="eyebrow">Engineering Science · robotics · machine learning · software</p>
  <h1>Projects</h1>
  <p class="lead">
    A focused view of my recent technical work across robot search, predictive modeling,
    embedded/software systems, machine learning, and engineering analysis.
  </p>
</section>

<section class="project-section">
  <h2>Featured Work</h2>
  <div class="project-grid featured-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>JavaScript</span>
        <span>Robotics + AI</span>
      </div>
      <h3>Position-History Belief 3D Visualizer</h3>
      <p>
        Interactive browser demo for position-history search-priority planning. It combines
        query-conditioned object belief maps, Bayesian updates, A* navigation, editable
        floorplans, and a Three.js replay for object-search scenarios.
      </p>
      <p class="project-note">Recent private prototype · updated July 2026</p>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Prognostics</span>
      </div>
      <h3>Jet Turbofan Remaining Useful Life with Neural ODEs</h3>
      <p>
        Research project using depth-continuous Neural ODE models for NASA CMAPSS
        turbofan sensor time series. Explored CNN-NODE variants to model degradation
        as a continuous-time dynamical system for safety-critical prediction.
      </p>
      <a class="project-link" href="https://github.com/EricHuang2FG/Predicting-the-Remaining-Useful-Life-of-Jet-Turbofan-Engines-Using-Depth-Continuous-Neural-ODEs">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>R</span>
        <span>Shiny App</span>
      </div>
      <h3>MIE286 Project</h3>
      <p>
        Team-built R/Shiny application with generated questions and reproducible
        dependency management through renv. Built as an engineering statistics and
        data workflow project.
      </p>
      <a class="project-link" href="https://github.com/derkychen/mie286-project">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Spiking ML</span>
      </div>
      <h3>Convolutional Spiking Neural Network</h3>
      <p>
        Biologically inspired CSNN trained on MNIST with snnTorch, PyTorch, LIF
        neurons, and surrogate-gradient learning over time-stepped inputs.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/convolutional-spiking-neural-network">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Machine Learning & Computer Vision</h2>
  <div class="project-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>LSTM</span>
      </div>
      <h3>Weather Prediction with LSTMs</h3>
      <p>
        Multi-step time-series forecasting model for Toronto weather data using
        sliding windows, PyTorch LSTMs, dropout regularization, and multi-target output.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Weather-Prediction-model-using-LSTMs">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>OpenCV</span>
      </div>
      <h3>Image Text Extractor</h3>
      <p>
        OCR pipeline using OpenCV preprocessing and Tesseract to identify image text
        regions, extract readable text, and save results for document automation tasks.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Image-Text-Extractor">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>OpenCV</span>
      </div>
      <h3>Face Detection</h3>
      <p>
        Real-time webcam face detection using Haar Cascade classifiers, bounding-box
        overlays, and tunable detection settings for different lighting conditions.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Face-Detection/tree/main">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>NumPy</span>
        <span>From Scratch</span>
      </div>
      <h3>Deep Neural Network for Image Classification</h3>
      <p>
        From-scratch neural network implementation for binary RGB image classification,
        including initialization, forward propagation, analytical backpropagation,
        cross-entropy loss, and gradient descent.
      </p>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Software Engineering</h2>
  <div class="project-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>C</span>
        <span>Algorithms</span>
      </div>
      <h3>Seam Carving in C</h3>
      <p>
        Content-aware image resizing implementation using energy maps, dynamic
        programming, and iterative low-energy seam removal.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/SeamCarver-C-Content-Aware-Image-Resizer">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>C</span>
        <span>Search</span>
      </div>
      <h3>Autocomplete Engine</h3>
      <p>
        Prefix lookup engine that retrieves top-weighted matches with preprocessing,
        binary search, predictable memory use, and fast query behavior.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/c-autocomplete-engine">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>NLP</span>
      </div>
      <h3>Semantic Similarity</h3>
      <p>
        Classical NLP project that builds word-context vectors from text and uses
        cosine similarity to predict related words and synonyms.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Semantic-Similarity">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Games</span>
      </div>
      <h3>Gomoku: Five in a Row</h3>
      <p>
        Python implementation of Gomoku with valid-move handling, board-state
        analysis, win detection, and AI-based move evaluation.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Gomuku-Five-in-a-Row-">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Engineering Analysis & MATLAB</h2>
  <div class="compact-list">
    <a href="https://github.com/ManiMajd89/Bridge-Analysis">Bridge Analysis</a>
    <a href="https://github.com/ManiMajd89/Two-Story-Building-Free-Vibration-Simulation">Two-Story Building Free Vibration Simulation</a>
    <a href="https://github.com/ManiMajd89/Initial-Value-Problem-Euler-Methods">Initial Value Problem Euler Methods</a>
    <a href="https://github.com/ManiMajd89/Least-Squares-fit">Least Squares Fit</a>
    <a href="https://github.com/ManiMajd89/Riemann-Sums-Approximating-a-Definite-Integral">Riemann Sums Approximation</a>
    <a href="https://github.com/ManiMajd89/Geometric-Series-Summation">Geometric Series Summation</a>
    <a href="https://github.com/ManiMajd89/MATLAB-Fundamentals">MATLAB Fundamentals</a>
  </div>
</section>

<section class="project-section">
  <h2>Additional Projects</h2>
  <div class="compact-list">
    <a href="https://github.com/ManiMajd89/Health-and-Hedons-Tracker">Health and Hedons Tracker</a>
    <a href="https://github.com/ManiMajd89/Scientific-Calculator">Scientific Calculator</a>
    <a href="https://github.com/ManiMajd89/Wordle-Blitz">Wordle Blitz</a>
    <a href="https://github.com/ManiMajd89/Gradual-Typing-Effect">Gradual Typing Effect</a>
    <a href="https://github.com/ManiMajd89/Cryptography">Cryptography</a>
    <a href="https://github.com/ManiMajd89/Youtube-Downloader">YouTube Downloader</a>
    <a href="https://github.com/ManiMajd89/EasyMath">EasyMath</a>
  </div>
</section>

<section class="project-section project-card research-card">
  <div class="project-meta">
    <span>Research</span>
    <span>Toronto Science Fair</span>
  </div>
  <h2>NeuroGenix Alpha</h2>
  <p>
    Theoretical research project proposing a recombinant protein design combining
    Sirtuin-6 and the catalytic domain of telomerase to explore neuroprotective
    strategies for Alzheimer's disease prevention. Awarded bronze at the 2024
    Toronto Science Fair.
  </p>
  <a class="project-link" href="https://github.com/ManiMajd89/ManiMajd89.github.io/blob/main/NeuroGenix-Aplha%20-%20Recombinant%20Brain%20Rehabilitating%20Protein.docx%20(1).pdf">Read research PDF</a>
</section>
