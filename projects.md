---
layout: default
title: Projects
---
<link rel="stylesheet" href="{{ '/style.css' | relative_url }}">

{% include navigation.html %}

<section class="page-hero">
  <p class="eyebrow">Engineering Science · robotics · machine learning · software</p>
  <h1>Projects</h1>
  <p class="lead">
    A curated set of projects I have built across robotics, machine learning,
    embedded systems, algorithms, numerical modeling, and applied engineering.
    Each project taught me something different about turning technical ideas into
    working systems.
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
        Interactive browser prototype for object-search planning in mapped indoor
        spaces. It turns object position histories into query-conditioned belief
        maps, updates those beliefs as a robot searches, and visualizes the process
        with editable floorplans, A* navigation, and a Three.js replay.
      </p>
      <p class="project-note">Private research prototype · updated July 2026</p>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Prognostics</span>
      </div>
      <h3>Jet Turbofan Remaining Useful Life with Neural ODEs</h3>
      <p>
        Research project on predicting aircraft engine degradation from NASA CMAPSS
        sensor data. The model treats remaining useful life as a continuous-time
        dynamical problem, using Neural ODE and CNN-NODE variants to compare against
        more conventional sequence models.
      </p>
      <a class="project-link" href="https://github.com/EricHuang2FG/Predicting-the-Remaining-Useful-Life-of-Jet-Turbofan-Engines-Using-Depth-Continuous-Neural-ODEs">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>R</span>
        <span>Shiny</span>
      </div>
      <h3>MIE286 Project</h3>
      <p>
        Team-built R/Shiny application for an engineering statistics workflow. The
        project uses generated app questions, a reproducible renv environment, and
        a structured app directory so the analysis can be run consistently by other
        contributors.
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
        MNIST classifier built with snnTorch and PyTorch to explore event-driven
        learning. The network uses leaky integrate-and-fire neurons, surrogate
        gradients, and time-stepped inputs to study how spiking models can perform
        image classification with sparse temporal computation.
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
        Multi-step weather forecasting model trained on Toronto weather data. It
        builds sliding-window time-series datasets, predicts several future steps at
        once, and uses a PyTorch LSTM with dropout and a reshaped output head for
        multi-variable prediction.
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
        OCR pipeline for extracting text from images, screenshots, and scanned
        documents. The project combines OpenCV preprocessing with Tesseract OCR to
        isolate text regions, convert them into readable text, and save the result
        for downstream use.
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
        Real-time webcam face detector using OpenCV and Haar Cascade classifiers.
        It captures frames from a live camera feed, marks detected faces with
        bounding boxes, and exposes simple parameters for improving detection under
        different lighting and camera conditions.
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
        From-scratch neural network implementation for binary RGB image
        classification. I implemented initialization, forward propagation,
        backpropagation, cross-entropy loss, and gradient descent directly in NumPy
        to understand the mechanics behind deeper image classifiers.
      </p>
      <p class="project-note">Course project · code not currently public</p>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Systems, Algorithms & Software</h2>
  <div class="project-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>Perl</span>
        <span>Zephyr RTC</span>
      </div>
      <h3>Firmware Onboarding Project</h3>
      <p>
        Real-time clock onboarding project for working with Zephyr firmware APIs.
        The task involves configuring RTC support, creating a small embedded app,
        and repeatedly logging date and time from a Zephyr device while navigating
        common build and device-tree setup issues.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/firmware-onboarding">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>C</span>
        <span>Image Algorithms</span>
      </div>
      <h3>Seam Carving in C</h3>
      <p>
        Content-aware image resizer written in C. The program computes pixel energy,
        uses dynamic programming to find low-energy vertical seams, and removes
        those seams while preserving the more visually important parts of an image.
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
        Weighted autocomplete engine built around sorted term data and binary
        search. It finds matching prefixes efficiently, ranks candidate completions
        by weight, and keeps the implementation small enough to reason about memory
        and runtime behavior directly.
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
        Classical NLP project that builds semantic descriptor vectors from text
        corpora and compares words with cosine similarity. It focuses on the core
        idea behind distributional semantics without relying on pretrained neural
        language models.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Semantic-Similarity">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Games & Interactive Tools</h2>
  <div class="project-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>AI Game Logic</span>
      </div>
      <h3>Gomoku: Five in a Row</h3>
      <p>
        Command-line Gomoku game with board validation, win detection, and an
        AI move evaluator. The project was a practical way to work through
        grid-based game state, scoring functions, and turn-by-turn decision logic.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Gomuku-Five-in-a-Row-">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Word Game</span>
      </div>
      <h3>Wordle Blitz</h3>
      <p>
        Custom Wordle-style game where players guess a five-letter word within a
        limited number of attempts. It handles guess validation, feedback for
        correct and misplaced letters, and replay flow in a simple Python program.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Wordle-Blitz">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Game</span>
      </div>
      <h3>Rock Paper Scissors Lizard Spock</h3>
      <p>
        Expanded version of Rock Paper Scissors with five move choices and two play
        modes. The program compares player choices against the full rule set and
        supports playing either against another person or against the computer.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Rock_Paper_Scissors_Lizard_Spock-">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Simulation</span>
      </div>
      <h3>Health and Hedons Tracker</h3>
      <p>
        Activity simulation that tracks health and happiness points over time.
        It models activities such as running, resting, and carrying textbooks while
        accounting for tiredness, star bonuses, and changing user state.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Health-and-Hedons-Tracker">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Utilities & Small Builds</h2>
  <div class="project-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>tkinter</span>
      </div>
      <h3>Scientific Calculator</h3>
      <p>
        Desktop calculator built with Python's tkinter library. It supports basic
        arithmetic alongside scientific operations, giving me practice with GUI
        layout, event handling, and input parsing.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Scientific-Calculator">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Math Tool</span>
      </div>
      <h3>EasyMath</h3>
      <p>
        Python calculator for common arithmetic, powers, roots, and trigonometric
        functions. The project focuses on making a small command-line math utility
        with clear operation selection and predictable numeric behavior.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/EasyMath">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>CLI Utility</span>
      </div>
      <h3>YouTube Downloader</h3>
      <p>
        Small downloader utility built around yt-dlp. It lets a user provide a
        video URL, choose an output location, and download the best available
        quality through a straightforward Python interface.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Youtube-Downloader">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Text Effect</span>
      </div>
      <h3>Gradual Typing Effect</h3>
      <p>
        Lightweight script that prints text character by character to create a
        terminal typing effect. It is a small but useful exercise in timing,
        terminal output, and presentation-oriented scripting.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Gradual-Typing-Effect">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>Python</span>
        <span>Cryptography</span>
      </div>
      <h3>Cryptography</h3>
      <p>
        Caesar cipher implementation for encoding and decoding messages with a
        configurable shift. The project is intentionally simple, focusing on string
        manipulation, modular arithmetic, and the basics of substitution ciphers.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Cryptography">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Engineering Analysis & MATLAB</h2>
  <div class="project-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>MATLAB</span>
        <span>Structures</span>
      </div>
      <h3>Bridge Analysis</h3>
      <p>
        CIV102 bridge-analysis project for evaluating a bridge under train loading.
        The MATLAB workflow calculates shear force, bending moment, and factors of
        safety to connect structural theory with a practical design problem.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Bridge-Analysis">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>MATLAB</span>
        <span>Dynamics</span>
      </div>
      <h3>Two-Story Building Free Vibration Simulation</h3>
      <p>
        Numerical simulation of a two-story building modeled as a coupled dynamic
        system. It compares Euler, Improved Euler, and analytical solutions to show
        how numerical method choice affects displacement predictions over time.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Two-Story-Building-Free-Vibration-Simulation">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>MATLAB</span>
        <span>Numerical Methods</span>
      </div>
      <h3>Initial Value Problem Euler Methods</h3>
      <p>
        Solver for a second-order initial value problem using Euler and Improved
        Euler methods. The project compares both numerical approximations with the
        analytical solution to make error behavior visible.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Initial-Value-Problem-Euler-Methods">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>MATLAB</span>
        <span>Regression</span>
      </div>
      <h3>Least Squares Fit</h3>
      <p>
        Polynomial least-squares fitting exercise using linear, quadratic, and cubic
        models. The script computes fit coefficients, evaluates error, and plots the
        fitted curves against the source data.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Least-Squares-fit">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>MATLAB</span>
        <span>Calculus</span>
      </div>
      <h3>Riemann Sums Approximation</h3>
      <p>
        Visualization of left and right Riemann sums for approximating a definite
        integral. The project compares numerical estimates with the analytical result
        as the number of subintervals changes.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Riemann-Sums-Approximating-a-Definite-Integral">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>MATLAB</span>
        <span>Series</span>
      </div>
      <h3>Geometric Series Summation</h3>
      <p>
        MATLAB comparison of partial sums and the analytical value of a geometric
        series. It uses iterative and vectorized calculations to show convergence as
        more terms are included.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Geometric-Series-Summation">View project</a>
    </article>

    <article class="project-card">
      <div class="project-meta">
        <span>MATLAB</span>
        <span>Reference</span>
      </div>
      <h3>MATLAB Fundamentals</h3>
      <p>
        Compact reference project collecting essential MATLAB commands and patterns.
        It serves as a quick-start guide for scripts, vectors, matrices, plotting,
        and common syntax used in introductory engineering computation.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/MATLAB-Fundamentals">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Research</h2>
  <div class="project-grid">
    <article class="project-card">
      <div class="project-meta">
        <span>Biology</span>
        <span>Toronto Science Fair</span>
      </div>
      <h3>NeuroGenix Alpha</h3>
      <p>
        Theoretical research project exploring a recombinant protein concept for
        Alzheimer's disease prevention. The proposal combines Sirtuin-6 and the
        catalytic domain of telomerase as a possible neuroprotective strategy and
        earned bronze at the 2024 Toronto Science Fair.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/ManiMajd89.github.io/blob/main/NeuroGenix-Aplha%20-%20Recombinant%20Brain%20Rehabilitating%20Protein.docx%20(1).pdf">Read research PDF</a>
    </article>
  </div>
</section>
