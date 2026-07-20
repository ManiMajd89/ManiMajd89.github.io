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
      <h3>Position-History Belief 3D Visualizer</h3>
      <p>
        Built an interactive Three.js research prototype for position-history-based
        object search across six mapped indoor environments. It turns object
        histories into query-conditioned belief maps, updates probabilities after
        detections and misses, and plans wall-safe routes with A*. Users can inspect
        belief components, replay each search in 3D, and move objects without
        changing the underlying floorplans.
      </p>
      <p class="project-note">Updated July 2026</p>
    </article>

    <article class="project-card">
      <h3>Jet Turbofan Remaining Useful Life with Neural ODEs</h3>
      <p>
        Co-developed Neural ODE and CNN-NODE models in PyTorch to estimate how many
        operating cycles remain before a turbofan reaches the end of its useful
        life. Trained on NASA's CMAPSS sensor histories, the CNN-NODE first extracts
        useful patterns before estimating remaining life. The models outperformed
        several published baselines on the fixed-condition FD001 and FD003
        benchmarks, and the work was published at IEEE ICPHM 2026.
      </p>
      <div class="project-links">
        <a class="project-link" href="https://doi.org/10.1109/ICPHM69567.2026.11585276">Read IEEE paper</a>
        <a class="project-link" href="https://github.com/EricHuang2FG/Predicting-the-Remaining-Useful-Life-of-Jet-Turbofan-Engines-Using-Depth-Continuous-Neural-ODEs">View code</a>
      </div>
    </article>

    <article class="project-card">
      <h3>OCT-EyeSNN: Retinal OCT Classification</h3>
      <p>
        Lead a five-member UTMIST team developing OCT-EyeSNN, a convolutional
        spiking neural network for four-category retinal OCT classification. I built
        the pipeline for preprocessing, spike encoding, unsupervised pretraining,
        and surrogate-gradient optimization. The model achieved 97.7% accuracy, a
        97.7% F1 score, and 98.0% precision. We also compare it with compact CNN and
        Vision Transformer baselines and use Intel Loihi simulation to study energy
        use, latency, and memory.
      </p>
    </article>

    <article class="project-card">
      <h3>Convolutional Spiking Neural Network</h3>
      <p>
        Built a convolutional spiking neural network in PyTorch and snnTorch to
        classify MNIST digits through output spike counts. Convolutional layers feed
        leaky integrate-and-fire neurons over 100 simulation steps, while surrogate
        gradients make the event-driven model trainable end to end. After one epoch,
        it reached 97.41% test accuracy on 10,000 images.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/convolutional-spiking-neural-network">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Machine Learning & Computer Vision</h2>
  <div class="project-grid">
    <article class="project-card">
      <h3>Weather Prediction with LSTMs</h3>
      <p>
        Built a multi-output PyTorch LSTM to forecast six future time steps from
        10-step windows of Toronto weather data. The model uses two recurrent layers,
        dropout, and a reshaped output head to predict several variables together.
        On held-out data, its best reported metrics were 0.8385 RMSE, 0.1276 MAE,
        and 0.0508 R².
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Weather-Prediction-model-using-LSTMs">View project</a>
    </article>

    <article class="project-card">
      <h3>Image Text Extractor</h3>
      <p>
        Built an OCR pipeline that converts text in photographs, screenshots, and
        scanned documents into editable output. OpenCV preprocesses each image and
        isolates text regions, which are cropped and resized before Tesseract
        performs recognition. The tool writes the extracted text to a file and also
        prints it in the terminal, keeping the workflow practical and easy to
        inspect.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Image-Text-Extractor">View project</a>
    </article>

    <article class="project-card">
      <h3>Face Detection</h3>
      <p>
        Built a real-time face detector that processes webcam frames with OpenCV's
        pretrained Haar cascade. The app marks each detected face with a labeled
        bounding box, supports adjustable detection parameters, and exits cleanly
        from the live feed. It demonstrates a complete capture, inference, and
        visualization loop without requiring a custom-trained model.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Face-Detection/tree/main">View project</a>
    </article>

    <article class="project-card">
      <h3>Deep Neural Network for Image Classification</h3>
      <p>
        Implemented an L-layer binary image classifier from scratch in NumPy to
        understand the mechanics hidden by machine-learning frameworks. I wrote
        parameter initialization, forward propagation, ReLU and sigmoid activations,
        binary cross-entropy, backpropagation, and gradient descent directly. Trained
        on RGB cat and non-cat images, the deeper model improved on a
        logistic-regression baseline through architecture and parameter tuning.
      </p>
      <p class="project-note">Code not currently public</p>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Systems, Algorithms & Software</h2>
  <div class="project-grid">
    <article class="project-card">
      <h3>Firmware Onboarding Project</h3>
      <p>
        Built a Zephyr RTOS onboarding application that initializes a real-time
        clock and logs relative date and time at a fixed interval. The work covered
        Kconfig, device-tree overlays, CMake and West builds, and debugging common
        RTC API and board-configuration failures. It provided hands-on experience
        developing embedded C inside a multi-contributor firmware repository.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/firmware-onboarding">View project</a>
    </article>

    <article class="project-card">
      <h3>MIE286 Project</h3>
      <p>
        Co-developed an R Shiny experiment for studying how timer feedback affects
        mental-arithmetic speed and accuracy. The app generates 40 reproducible
        arithmetic questions, records per-question response times and correctness,
        and exports participant summaries. An R analysis pipeline compares feedback
        groups using visualizations, normality and variance checks, t-tests, and
        Pearson correlation.
      </p>
      <a class="project-link" href="https://github.com/derkychen/mie286-project">View project</a>
    </article>

    <article class="project-card">
      <h3>Seam Carving in C</h3>
      <p>
        Implemented content-aware image resizing in C by repeatedly removing
        low-energy vertical seams from raw RGB images. The program computes
        dual-gradient pixel energies, uses dynamic programming to build cumulative
        seam costs, backtracks the minimum path, and writes each reduced image.
        Unlike simple cropping, it preserves higher-energy edges and important
        content as image width decreases.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/SeamCarver-C-Content-Aware-Image-Resizer">View project</a>
    </article>

    <article class="project-card">
      <h3>Autocomplete Engine</h3>
      <p>
        Built a weighted autocomplete engine in C using sorted term records and
        binary search to locate the first and last matches for a prefix. Matching
        terms are ranked by descending weight with qsort, keeping lookup overhead
        low without a trie. The implementation handled more than 90,000 city names;
        documented tests reported sub-2 ms lookups on 50,000 terms.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/c-autocomplete-engine">View project</a>
    </article>

    <article class="project-card">
      <h3>Semantic Similarity</h3>
      <p>
        Built a classical NLP system that learns word meaning from context rather
        than pretrained embeddings. It tokenizes text corpora, constructs
        co-occurrence-based semantic descriptor vectors, and uses cosine similarity
        to choose the closest word from a set of candidates. A separate evaluation
        routine compares predictions with labeled answers, making word-association
        accuracy directly measurable.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Semantic-Similarity">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Games & Interactive Tools</h2>
  <div class="project-grid">
    <article class="project-card">
      <h3>Gomoku: Five in a Row</h3>
      <p>
        Built a command-line Gomoku game where a player competes against an AI on an
        8×8 board. The program validates moves, detects five-in-a-row wins, analyzes
        open sequences, and scores candidate positions to choose the computer's next
        move. It combines board-state representation, rule checking, and explainable
        heuristic decision logic in a complete turn-based game.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Gomuku-Five-in-a-Row-">View project</a>
    </article>

    <article class="project-card">
      <h3>Wordle Blitz</h3>
      <p>
        Built a Python Wordle-style game that gives players six attempts to identify
        a five-letter word. Each guess is validated and compared position by
        position, with distinct feedback for correct letters, misplaced letters,
        and misses. The program manages attempt limits and win and loss states, then
        reveals the target word when all six guesses are used.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Wordle-Blitz">View project</a>
    </article>

    <article class="project-card">
      <h3>Rock Paper Scissors Lizard Spock</h3>
      <p>
        Built a command-line implementation of Rock Paper Scissors Lizard Spock with
        all 10 winning relationships encoded explicitly. Players can choose a
        two-person game or face a computer opponent whose move is selected randomly.
        The program validates inputs, resolves ties and wins, and supports replaying
        with a different mode after each round.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Rock_Paper_Scissors_Lizard_Spock-">View project</a>
    </article>

    <article class="project-card">
      <h3>Health and Hedons Tracker</h3>
      <p>
        Built a stateful Python simulation that tracks health and hedons as a user
        runs, rests, or carries textbooks. Activity rewards change with duration,
        tiredness, and time-limited star bonuses, so the same action can have
        different effects over time. Helper functions update cumulative state and
        recommend the most enjoyable activity for the next minute.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Health-and-Hedons-Tracker">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Utilities & Small Builds</h2>
  <div class="project-grid">
    <article class="project-card">
      <h3>Scientific Calculator</h3>
      <p>
        Built a desktop scientific calculator with Python and Tkinter, combining
        basic arithmetic with powers, roots, logarithms, and trigonometric
        functions. A button-driven interface assembles and evaluates expressions,
        while dedicated handlers manage scientific operations and format decimal
        results to five places. The project combines GUI layout, event handling,
        expression parsing, and numerical input validation.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Scientific-Calculator">View project</a>
    </article>

    <article class="project-card">
      <h3>EasyMath</h3>
      <p>
        Built a command-line calculator in Python covering 21 operations, from
        arithmetic and powers to roots, factorials, logarithms, and six
        trigonometric functions. Each operation is implemented separately and
        selected through a repeatable text menu. The project emphasizes predictable
        numeric behavior, clear input flow, and decomposition into small reusable
        functions.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/EasyMath">View project</a>
    </article>

    <article class="project-card">
      <h3>YouTube Downloader</h3>
      <p>
        Built a small Python utility around yt-dlp for saving videos from a supplied
        YouTube URL. The program requests an output directory, selects the best
        available quality, and reports progress through a straightforward
        command-line flow. It wraps a capable download library in a simpler
        interface while keeping file location and download behavior explicit.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Youtube-Downloader">View project</a>
    </article>

    <article class="project-card">
      <h3>Gradual Typing Effect</h3>
      <p>
        Built a Python text animation that reveals a user-provided phrase one
        character at a time. At each alphabetic position, the script cycles from
        "a" to the target letter, refreshes the same terminal line, and pauses 0.1
        seconds between updates. The result is a rolling letter-transition effect
        built with nested iteration, timing, and terminal control.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Gradual-Typing-Effect">View project</a>
    </article>

    <article class="project-card">
      <h3>Cryptography</h3>
      <p>
        Implemented a Caesar cipher in Python for encrypting and decrypting messages
        with a user-supplied shift key. The program maps characters through ASCII
        values, applies modular shifts, and reconstructs readable output while
        preserving the reversible relationship between both operations. It is a
        compact demonstration of string processing, modular arithmetic, and
        key-based substitution.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Cryptography">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Engineering Analysis & MATLAB</h2>
  <div class="project-grid">
    <article class="project-card">
      <h3>Bridge Analysis</h3>
      <p>
        Analyzed a 1,200 mm bridge under a 400 N, six-point train load using MATLAB.
        The script sweeps 345 train positions to generate shear-force and
        bending-moment envelopes, then evaluates tensile, compressive, shear, glue,
        and buckling failure modes. It produces factor-of-safety calculations and
        structural diagrams that connect load placement with governing design
        limits.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Bridge-Analysis">View project</a>
    </article>

    <article class="project-card">
      <h3>Two-Story Building Free Vibration Simulation</h3>
      <p>
        Modeled free vibration of a two-story building as a coupled four-state
        system in MATLAB. An Improved Euler solver propagates floor displacement and
        velocity over 10 seconds, and runs with 400, 500, and 1,000 time steps are
        plotted side by side. The comparison shows how temporal resolution affects
        the numerical response of both floors.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Two-Story-Building-Free-Vibration-Simulation">View project</a>
    </article>

    <article class="project-card">
      <h3>Initial Value Problem Euler Methods</h3>
      <p>
        Solved a second-order initial-value problem in MATLAB with Euler and Improved
        Euler methods, then compared both against the closed-form solution over 10
        seconds. The script evaluates five step counts from 45 to 250 and plots each
        approximation. Improved Euler reaches useful accuracy with fewer steps, with
        N=55 identified as a practical balance.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Initial-Value-Problem-Euler-Methods">View project</a>
    </article>

    <article class="project-card">
      <h3>Least Squares Fit</h3>
      <p>
        Compared linear, quadratic, and cubic least-squares models for the
        relationship between LSAT and GPA data. The MATLAB script constructs each
        fit, calculates its coefficients and mean-squared error, and plots all three
        curves against the observations. This makes the tradeoff between model
        complexity and residual error visible instead of selecting a polynomial by
        appearance alone.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Least-Squares-fit">View project</a>
    </article>

    <article class="project-card">
      <h3>Riemann Sums Approximation</h3>
      <p>
        Visualized left and right Riemann-sum approximations for the integral of
        sqrt(x+1) from 0 to 3. The MATLAB script increases the number of subintervals
        from 10 to 100 and compares both estimates with the analytical value 14/3.
        The plot shows the two numerical sequences converging toward the exact
        integral from opposite sides.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Riemann-Sums-Approximating-a-Definite-Integral">View project</a>
    </article>

    <article class="project-card">
      <h3>Geometric Series Summation</h3>
      <p>
        Compared iterative and vectorized calculations of a geometric series with
        first term 1 and common ratio 1/4. The MATLAB script computes the first 20
        partial sums, plots them against the exact infinite sum 4/3, and shows how
        quickly both implementations converge. The exercise connects loop-based
        computation, array operations, and analytical validation.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/Geometric-Series-Summation">View project</a>
    </article>

    <article class="project-card">
      <h3>MATLAB Fundamentals</h3>
      <p>
        Created a compact MATLAB reference covering arrays, matrices, indexing,
        mathematical operations, logical expressions, control flow, functions, and
        plotting. Each section can be run independently to inspect its output,
        making the script useful as both an introductory exercise and a practical
        syntax reference. The project establishes patterns reused throughout later
        numerical-analysis work.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/MATLAB-Fundamentals">View project</a>
    </article>
  </div>
</section>

<section class="project-section">
  <h2>Research</h2>
  <div class="project-grid">
    <article class="project-card">
      <h3>NeuroGenix Alpha</h3>
      <p>
        Developed a theoretical recombinant-protein proposal exploring whether a
        construct combining SIRT6 with the catalytic domain of telomerase could
        support neuroprotection relevant to Alzheimer's disease. The report connects
        literature on DNA repair, telomere maintenance, and protein design into a
        testable research concept. It earned a bronze award at the 2024 Toronto
        Science Fair.
      </p>
      <a class="project-link" href="https://github.com/ManiMajd89/ManiMajd89.github.io/blob/main/NeuroGenix-Aplha%20-%20Recombinant%20Brain%20Rehabilitating%20Protein.docx%20(1).pdf">Read research PDF</a>
    </article>
  </div>
</section>
