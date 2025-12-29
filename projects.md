---
layout: default
title: Projects
---
<link rel="stylesheet" href="style.css">

<nav>
  <ul style="list-style-type: none; padding: 0; display: flex; gap: 1rem; background-color: #f8f9fa; padding: 10px; border-bottom: 2px solid #ddd;">
    <li><a href="/" style="text-decoration: none; font-weight: bold;">🏠 Home</a></li>
    <li><a href="/portfolio" style="text-decoration: none; font-weight: bold;">📄 Portfolio</a></li>
    <li><a href="/projects" style="text-decoration: none; font-weight: bold;">🛠️ Projects</a></li>
    <li><a href="/contact" style="text-decoration: none; font-weight: bold;">📞 Contact Me</a></li>
  </ul>
</nav>


# 🛠️ My Projects

Welcome to my project showcase! Here you’ll find a curated list of my most notable projects, categorized by programming languages and domains.

---
## 🤖 Machine Learning & AI Projects

💻 **Predicting the Remaining Useful Life (RUL) of Jet Turbofan Engines Using Neural ODEs**
🔗 [View Project](https://github.com/EricHuang2FG/Predicting-the-Remaining-Useful-Life-of-Jet-Turbofan-Engines-Using-Depth-Continuous-Neural-ODEs) 

A research-focused project investigating depth-continuous Neural Ordinary Differential Equations (NODEs) for predicting the Remaining Useful Life of jet turbofan engines using NASA’s CMAPSS time-series sensor dataset. Unlike discrete-depth LSTM and CNN models, the NODE framework models engine degradation as a continuous-time dynamical system, better aligning with the underlying physical processes and multi-scale sensor dynamics. A CNN–NODE variant was also explored to extract local temporal patterns before continuous-time modeling. The proposed approach achieved the lowest RMSE on fixed operating-condition datasets, reducing prediction error by approximately 44% compared to a CNN–LSTM–Attention baseline, and improved performance on multi-condition datasets with an additional 28% RMSE reduction, demonstrating superior stability and long-horizon prediction accuracy in safety-critical prognostics.


💻 **Convolutional Spiking Neural Network (CSNN) using snnTorch**
🔗 [View Project](https://github.com/ManiMajd89/convolutional-spiking-neural-network)  

A biologically inspired Convolutional Spiking Neural Network trained from scratch on the MNIST dataset using Leaky Integrate-and-Fire neurons and surrogate-gradient backpropagation. The model processes each input over 100 discrete time steps, enabling temporal integration and sparse, event-driven computation instead of a single forward pass. Despite being trained for only one epoch, the network achieved a final test accuracy of 97.41%, with accuracy rapidly improving after early iterations, surpassing 95% by iteration 200 and stabilizing above 97% by iteration 350, demonstrating state-of-the-art performance for shallow spiking networks trained from scratch.


💻 **Deep Neural Network for Image Classification**
🔗 [View Project]

A fully from-scratch implementation of deep neural networks for binary classification of RGB images as cat vs non-cat, developed without using machine learning libraries for core computations. The project implements all fundamental components, including parameter initialization, forward propagation, backpropagation with analytical gradients, binary cross-entropy loss, and gradient-descent optimization using NumPy. By increasing network depth from two to four layers and refining training dynamics, the model improved classification accuracy from 72% to 80%, clearly demonstrating the impact of network depth and optimization on learning expressive visual representations.


💻 **Weather Prediction using LSTMs**  
🔗 [View Project](https://github.com/ManiMajd89/Weather-Prediction-model-using-LSTMs)  

A time-series forecasting project using a multi-layer LSTM network in PyTorch to predict Toronto weather variables through multi-step forecasting. The model was trained using a sliding-window data generator with a 10-step lookback and a 6-step forecast horizon, enabling prediction across multiple future time steps and target variables. Dropout regularization and a reshaped linear output head were used to improve stability and generalization. When evaluated on a held-out test set, the model achieved an RMSE of 0.8385, MAE of 0.1276, and R² score of 0.0508, demonstrating measurable performance gains over baseline approaches and validating the effectiveness of sequence-based modeling for weather prediction.

💻 **Text Detection and Extraction From Images**
🔗 [View Project](https://github.com/ManiMajd89/Image-Text-Extractor) 

This project automates the extraction of textual information from images. Built using OpenCV and Tesseract OCR, it preprocesses images, identifies text regions, and extracts text with precision. The program outputs the extracted text to a .txt file while also displaying it in the terminal, making it a powerful tool for processing scanned documents, photos, or screenshots.

💻 **Face Detection**  
🔗 [View Project](https://github.com/ManiMajd89/Face-Detection/tree/main)  
A real-time face detection project using OpenCV. This program captures video from a webcam, detects faces in the feed using a Haar Cascade classifier, and labels them with customizable text. It can serve as a foundation for advanced object detection projects.




## 🧮 **MATLAB Projects**
💡 **Bridge Analysis**  
🔗 [View Project](https://github.com/ManiMajd89/Bridge-Analysis)  
A structural analysis tool for bridges subjected to train loading, demonstrating expertise in MATLAB and civil engineering principles.

💡 **Two-Story Building Free Vibration Simulation**  
🔗 [View Project](https://github.com/ManiMajd89/Two-Story-Building-Free-Vibration-Simulation)  
Simulates free vibration of a two-story building using numerical methods and analytical solutions.

💡 **Initial Value Problem Euler Methods**  
🔗 [View Project](https://github.com/ManiMajd89/Initial-Value-Problem-Euler-Methods)  
Solves second-order IVPs using numerical methods, comparing results with analytical solutions.

💡 **Least Squares Fit**  
🔗 [View Project](https://github.com/ManiMajd89/Least-Squares-fit)  
Models GPA and LSAT relationships using polynomial regression and evaluates errors.

💡 **Riemann Sums Approximation**  
🔗 [View Project](https://github.com/ManiMajd89/Riemann-Sums-Approximating-a-Definite-Integral)  
Visualizes and compares Riemann sums with analytical integration solutions.

💡 **Geometric Series Summation**  
🔗 [View Project](https://github.com/ManiMajd89/Geometric-Series-Summation)  
Highlights the differences between analytical and partial sums of a geometric series.

💡 **MATLAB Fundamentals**  
🔗 [View Project](https://github.com/ManiMajd89/MATLAB-Fundamentals)  
A reference for MATLAB beginners covering fundamental commands and concepts.

---
##  **Software Engineering Projects**

💻 **Seam Carving in C**
🔗 [View Project](https://github.com/ManiMajd89/SeamCarver-C-Content-Aware-Image-Resizer)  

A C implementation of content-aware image resizing using seam carving. The project computes pixel energy maps, identifies minimum-energy seams using dynamic programming, and removes seams to resize images while preserving important visual features, demonstrating efficient algorithm design and low-level memory control.


💻 **Autocomplete Engine in C**
🔗 [View Project](https://github.com/ManiMajd89/c-autocomplete-engine)  

A fast, memory-efficient autocomplete engine written in C that supports prefix-based search using static preprocessing and binary search on sorted datasets. The implementation avoids dynamic trie structures, enabling low-latency queries with predictable performance and clean systems-level code.


💻 **Semantic Similarity**  
🔗 [View Project](https://github.com/ManiMajd89/Semantic-Similarity)  
NLP-based project that evaluates semantic similarity using cosine similarity.

💻 **Health and Hedons Tracker**  
🔗 [View Project](https://github.com/ManiMajd89/Health-and-Hedons-Tracker)  
Tracks health and happiness points based on user activities.

💻 **Gomoku: Five in a Row**  
🔗 [View Project](https://github.com/ManiMajd89/Gomuku-Five-in-a-Row-)  
A Python implementation of the classic Gomoku game with AI integration.

💻 **Scientific Calculator**  
🔗 [View Project](https://github.com/ManiMajd89/Scientific-Calculator)  
A GUI-based calculator with scientific functionalities built using Python's tkinter library.

💻 **Wordle Blitz**  
🔗 [View Project](https://github.com/ManiMajd89/Wordle-Blitz)  
A custom implementation of the popular Wordle game.

💻 **Gradual Typing Effect**  
🔗 [View Project](https://github.com/ManiMajd89/Gradual-Typing-Effect)  
A dramatic typing effect script inspired by classic hacker movies.

💻 **Cryptography**  
🔗 [View Project](https://github.com/ManiMajd89/Cryptography)  
Implements a Caesar cipher for encrypting and decrypting messages.

💻 **Rock Paper Scissors Lizard Spock**  
🔗 [View Project](https://github.com/ManiMajd89/Rock_Paper_Scissors_Lizard_Spock-)  
A fun twist on the classic Rock Paper Scissors game.

💻 **YouTube Downloader**  
🔗 [View Project](https://github.com/ManiMajd89/Youtube-Downloader)  
A script to download YouTube videos in the best available quality.

💻 **EasyMath**  
🔗 [View Project](https://github.com/ManiMajd89/EasyMath)  
A versatile Python-based calculator for basic and advanced math operations.

---

## 🌟 **Other Notable Projects**
🧠 **NeuroGenix Alpha**  
NeuroGenix Alpha is a theoretical research project aimed at combating Alzheimer’s disease through innovative neuroprotective biologics.

- **Description**: Developed a recombinant protein combining Sirtuin-6 (SIRT6) and the catalytic domain of telomerase (TERT) to repair DNA damage and maintain telomere length, addressing aging and neurodegeneration.
  
- **Highlights**:
  - Designed for intranasal administration to cross the blood-brain barrier.
  - Targets oxidative stress in brain cells for age-delaying and neuroprotective effects.

### Achievements
- 🏅 **Award**:  
  Received the **Bronze Medal** at the **2024 Toronto Science Fair** for the project *NeuroGenix Alpha: A Theoretical Recombinant Protein for Alzheimer’s Disease Prevention*.

### Resources
- 📄 **[Research PDF](https://github.com/ManiMajd89/ManiMajd89.github.io/blob/main/NeuroGenix-Aplha%20-%20Recombinant%20Brain%20Rehabilitating%20Protein.docx%20(1).pdf)**  
  Read the detailed research report for an in-depth understanding of the project.

- 🔗 **[LinkedIn Post](https://www.linkedin.com/in/mani-majd/details/honors/urn:li:fsd_profileHonor:(ACoAAEbsh-kBD3Xdqqflls6vyqvqHPlxcq9-Xos,181401085)/treasury/)**  
  View the LinkedIn post for a concise summary and community recognition.


---

Feel free to explore these projects and reach out to collaborate on new ideas!
