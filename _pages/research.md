---
layout: portfolio
title: "Research"
permalink: /research/
hide_title: true
excerpt: "Experimental nanobiotechnology and machine learning for DNA-nanotube optical sensing."
---

<section class="page-banner">
  <h1>Research</h1>
  <p class="keywords">Chemical engineering<span>|</span>Machine learning<span>|</span>Experimental nanobiotechnology<span>|</span>Nanobiosensors</p>
</section>

<p class="statement">I design optical sensors made of <strong>carbon nanotubes wrapped in short DNA strands</strong> (ssDNA-SWCNTs). These sensors glow in the <strong>near-infrared</strong>, and the glow changes when a target molecule interacts with the DNA. The DNA sequence decides what the sensor responds to, and there are about 10<sup>18</sup> possible sequences, far too many to test in the lab. So I use <strong>sequence clustering</strong>, <strong>high-throughput screening</strong>, and <strong>deep learning</strong> to find the good ones. I have applied this approach to four very different targets.</p>

<div class="study" id="glucose">
  <span class="tag">01 / Glucose</span>
  <h2>Non-enzymatic optical glucose sensing</h2>
  <p>People with diabetes need to track their glucose levels, but most continuous glucose sensors use <strong>enzymes</strong>, and these enzymes release by-products that can be inflammatory and toxic. DNA-nanotube sensors could work <strong>without enzymes</strong>, but before this work no DNA sequence had been found that makes them respond to glucose.</p>
  <p>I used clustering to design a <strong>diverse library of 90 DNA sequences</strong>, based on sequence similarity, k-mer motifs, and predicted folding. I screened the library by near-infrared fluorescence in 384-well plates, then improved the best sequence with <strong>mutations chosen by deep learning and pattern recognition</strong>. The mutation and machine learning rounds gave higher responses than clustering alone. The final sensors respond to glucose in a concentration-dependent way, with changes in both brightness and emission wavelength, and they still respond in 10% serum.</p>
  <p class="approach">Clustering-based library design → 384-well NIR screening → deep learning guided mutation → validation</p>
  <div class="pub-links">
    <a href="https://doi.org/10.1101/2025.05.06.652529">Preprint</a>
    <a href="https://github.com/YahyaRabbani20/AI-BioSense">Code</a>
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
  </div>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P1a.png' | relative_url }}" alt="Violin plot of glucose-induced intensity change for clustering, mutation and clustering, and ML prediction" loading="lazy">
      <figcaption><b>(a)</b> Glucose-induced intensity change for three ways of selecting sequences: clustering, mutation and clustering, and ML prediction.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P1b.png' | relative_url }}" alt="Concentration-dependent intensity change and peak shift with sigmoid fits" loading="lazy">
      <figcaption><b>(b)</b> Intensity change (red) and peak shift (blue) at different glucose concentrations, fitted with a sigmoid model.</figcaption>
    </figure>
  </div>
</div>

<div class="study" id="opg">
  <span class="tag">02 / OPG protein</span>
  <h2>Clustering-assisted directed evolution for OPG sensing</h2>
  <p>Osteoprotegerin (OPG) is a <strong>protein linked to cancer</strong>. Detecting a protein with an optical sensor is hard because blood contains many other proteins, so the sensor has to <strong>respond to OPG and ignore the rest</strong>.</p>
  <p>I started from a computer-generated library of <strong>one million DNA sequences</strong> and picked 48 candidates using several sequence representations. Then I ran <strong>repeated rounds of mutation, clustering, and screening</strong>. Over three generations, the OPG signal of the (7,6) nanotube grew from about 1.1 nm to between 2.2 and 2.8 nm, while the signal for the control protein BSA stayed around 1 to 1.5 nm. In other words, the sensors became <strong>both stronger and more selective</strong> under our test conditions. We also used the screening data to train neural networks, which suggested more high-response candidates.</p>
  <p class="approach">One million sequences → 48 cluster-selected candidates → three rounds of mutation and re-clustering → deep learning prediction</p>
  <p class="note">Manuscript in submission. These results come from lab tests, and clinical performance still needs to be validated.</p>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P2a.png' | relative_url }}" alt="Bar chart of (7,6) peak shift for OPG and BSA across three generations for families OPGM10 and OPGM14" loading="lazy">
      <figcaption><b>(a)</b> Peak shift of the (7,6) nanotube for OPG and for the control protein BSA over three generations of directed evolution, in two sequence families (OPGM10 and OPGM14).</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P2b.png' | relative_url }}" alt="Heatmap of peak-shift responses across cluster-selected DNA variants" loading="lazy">
      <figcaption><b>(b)</b> Peak shift responses of the cluster-selected DNA variants.</figcaption>
    </figure>
  </div>
</div>

<div class="study" id="nitric-oxide">
  <span class="tag">03 / Nitric oxide</span>
  <h2>Linking DNA sequence to nitric oxide response</h2>
  <p>Nitric oxide (NO) is a short-lived signaling molecule that plays a central role in <strong>inflammation</strong>. That makes it useful to monitor but hard to measure. A good NO sensor needs to be <strong>bright</strong> enough to read and also <strong>dim strongly</strong> when NO is present.</p>
  <p>I combined <strong>sequence representations, pattern recognition, and machine learning</strong> to find which bases at which positions are linked to a strong NO response, and used these patterns to choose new sequences. The sequences picked by machine learning were mostly <strong>bright and strongly quenched</strong>, at about 85 to 92% quenching, compared with sequences picked by clustering alone. This work is a step toward sensors for monitoring inflammation.</p>
  <p class="approach">Clustering → position and motif analysis → machine learning selection → brightness and quenching screening</p>
  <p class="note">Manuscript in submission. Related work: Zubkovs et al., <em>Biosensors and Bioelectronics</em> 293, 118092 (2026), an electronics-free optical sensor for nitric oxide in inflammatory responses.</p>
  <div class="pub-links">
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
  </div>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P3a.png' | relative_url }}" alt="3D surface of mean quenching response by DNA position and base" loading="lazy">
      <figcaption><b>(a)</b> Average quenching response for each base (A, C, G, T) at each position in the DNA sequence.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P3b.png' | relative_url }}" alt="Scatter plot of NO-induced quenching versus PL intensity for clustering, pattern recognition, and ML prediction" loading="lazy">
      <figcaption><b>(b)</b> Sensor brightness (PL intensity) against NO quenching for sequences selected by clustering, pattern recognition, and ML prediction.</figcaption>
    </figure>
  </div>
</div>

<div class="study" id="mycotoxin">
  <span class="tag">04 / Mycotoxins</span>
  <h2>Predictive sequence selection for fumonisin B1</h2>
  <p>Fumonisin B1 (FB1) is a <strong>toxin made by fungi</strong> that contaminates corn and corn-based food. Current lab methods work well but are slow and expensive, so a <strong>fast optical sensor</strong> would be useful, if we can find the right DNA sequence.</p>
  <p>I trained <strong>neural networks and support vector machines</strong> on the measured responses of DNA-nanotube sensors to FB1. The models sorted sequences into high and low responders, using a 1.5 nm peak shift as the cutoff, with <strong>over 80% accuracy</strong>. I then used them to predict <strong>new mutants and completely different DNA sequences</strong>, and tested these in the lab to see whether the predictions held outside the training data.</p>
  <p class="approach">Experimental training set → neural network and SVM classification with cross-validation → prediction of new sequences → lab validation</p>
  <div class="pub-links">
    <a href="https://doi.org/10.1101/2023.09.07.556334">Preprint</a>
    <a href="https://github.com/YahyaRabbani20/ML-Models-Opticalsensor-Mycotoxin-Detection">Code</a>
  </div>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P4a.png' | relative_url }}" alt="Measured peak-shift responses of DNA sequences with predicted probability of high response shown by marker size" loading="lazy">
      <figcaption><b>(a)</b> Measured peak shift for each sequence, with marker size showing the predicted chance of a high response. The dashed line is the 1.5 nm cutoff.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P4b.png' | relative_url }}" alt="Experimental responses for the training set, predicted mutants, and dissimilar DNA sequences, marking classifications and misclassifications" loading="lazy">
      <figcaption><b>(b)</b> Lab results for the training set, the predicted mutants, and the dissimilar sequences, with correct and incorrect predictions marked.</figcaption>
    </figure>
  </div>
</div>

## A broader chemical engineering foundation
My earlier work spans magnetorheological materials, experimental rheology, neural-network and support-vector-regression models, computational fluid dynamics, and process optimization. These foundational skills support my experimental design, sensing, and machine-learning approach to DNA-nanotube optical systems.

[Browse my full publication record on Google Scholar ↗](https://scholar.google.com/citations?user=gk2vj4YAAAAJ&hl=en)
