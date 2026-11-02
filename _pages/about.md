---
layout: portfolio
permalink: /
title: "AI-Guided Design and Automated Experiments for Novel Nanosensors"
excerpt: "An AI-guided discovery platform that designs, prepares, measures, and learns from DNA-wrapped carbon nanotube sensors."
home: true
redirect_from:
  - /about/
  - /about.html
---

<section class="hero">
  <div>
    <p class="eyebrow">AI-guided discovery platform</p>
    <h1 style="font-size:clamp(34px,4.2vw,54px)">AI-Guided Design and Automated Experiments for <em>Novel Nanosensors</em></h1>
    <p class="lead">DNA-wrapped carbon nanotubes glow in the near-infrared, and their glow changes when a target molecule binds. The DNA sequence decides which molecule the sensor responds to, but a 30-base strand alone has about 10<sup>18</sup> possible sequences. This platform searches that space in a loop. It designs a small and diverse set of sequences, prepares and screens them in 384-well plates, measures their optical response automatically, and uses machine learning to pick what to test next. Each round of data improves the next round of predictions.</p>
    <p class="note">The same approach has been applied to glucose, the cancer protein OPG, nitric oxide, and the food toxin fumonisin B1. European patent application EP 24211885.9.</p>
    <div class="buttons">
      <a class="button primary" href="{{ '/research/' | relative_url }}">See the research</a>
      <a class="button" href="{{ '/vision/' | relative_url }}">Research vision</a>
    </div>
  </div>
  <figure class="hero-figure">
    <img src="{{ '/images/Image_H_All.png' | relative_url }}" alt="Discovery funnel narrowing a large pool of DNA sequences through a neural network to a few responsive sensors">
    <figcaption>The discovery funnel. A very large pool of DNA sequences is narrowed down by experiments and machine learning to a few sensors with the right optical response.</figcaption>
  </figure>
</section>

<section class="band" id="platform">
  <p class="eyebrow">How the platform works</p>
  <h2>Design, prepare, measure, learn</h2>
  <p class="lead">Four steps repeat in a loop. Each round tests only a small number of sequences, but the results train the models that choose the next set.</p>
  <div class="thrust">
    <figure class="thrust-media step-media">
      <img src="{{ '/images/Image_H_Design.png' | relative_url }}" alt="Sequence representations by alignment, k-mer composition, and predicted folding, followed by clustering and selection of diverse sequences" loading="lazy">
    </figure>
    <div>
      <span class="tag">Step 1 · Design</span>
      <h3>Sequence selection and predictive modeling</h3>
      <p>Candidate DNA sequences are described in three ways: how similar they are to each other (MAFFT alignment), which short motifs they contain (k-mers), and how they are likely to fold. Clustering these descriptions splits the sequence space into groups, and one representative is picked from each group.</p>
      <p>The result is a small set that still covers the variety of the whole space, so very few experiments are wasted.</p>
    </div>
  </div>
  <div class="thrust reverse">
    <figure class="thrust-media step-media">
      <img src="{{ '/images/Image_H_Prepare.png' | relative_url }}" alt="DNA exchange onto carbon nanotubes and robotic liquid handling into multi-well plates with analyte and reference wells" loading="lazy">
    </figure>
    <div>
      <span class="tag">Step 2 · Prepare</span>
      <h3>Automated sample preparation and screening</h3>
      <p>Each selected sequence is wrapped onto carbon nanotubes by replacing the original surfactant (sodium cholate) with DNA. The samples are brought to the same concentration and placed in 384-well plates with either the target molecule or a buffer blank, in triplicate with matched controls.</p>
      <p>A pipetting robot can run this step, which keeps volumes and timing the same across every plate.</p>
    </div>
  </div>
  <div class="thrust">
    <figure class="thrust-media step-media">
      <img src="{{ '/images/Image_H_Measure.png' | relative_url }}" alt="Near-infrared microscope with 655 and 735 nm excitation and InGaAs detector, and the Python processing pipeline" loading="lazy">
    </figure>
    <div>
      <span class="tag">Step 3 · Measure</span>
      <h3>Automated near-infrared plate scanning</h3>
      <p>A custom near-infrared microscope excites each well at 655 and 735 nm and records the fluorescence with an InGaAs detector, while a LabVIEW program moves through the plate.</p>
      <p>A Python pipeline then cleans each spectrum, fits the peak of each nanotube type, and extracts the change in brightness and peak position. This gives one response value for every sequence and nanotube type.</p>
    </div>
  </div>
  <div class="thrust reverse">
    <figure class="thrust-media step-media">
      <img src="{{ '/images/Image_H_Learn.png' | relative_url }}" alt="Optical response data, pattern recognition of positions and motifs, and ensemble learning with CNN, GNN, and GCN models" loading="lazy">
    </figure>
    <div>
      <span class="tag">Step 4 · Learn</span>
      <h3>Train models and choose the next candidates</h3>
      <p>The measured responses train three neural networks (CNN, GNN, and GCN), each of which reads the DNA in a different way. Pattern recognition finds which bases and motifs are linked to strong responses and uses them to generate new candidate sequences.</p>
      <p>The models then vote on these candidates, and the most promising ones go back to the lab. That closes the loop and starts the next round.</p>
    </div>
  </div>
</section>

<section class="band">
  <p class="eyebrow">Current focus</p>
  <div class="foundation">
    <article>
      <h3>AI-guided materials design</h3>
      <p>Using clustering, deep learning, and active experimentation to discover new biosensor sequences and materials faster and more reliably.</p>
    </article>
    <article>
      <h3>Optical nanobiosensors</h3>
      <p>Engineering ssDNA-wrapped carbon nanotube systems for selective detection of glucose, nitric oxide, cancer biomarkers, and mycotoxins.</p>
    </article>
    <article>
      <h3>Data-driven experimentation</h3>
      <p>Connecting automated high-throughput screening, spectroscopy, and machine-learning-guided design to accelerate discovery.</p>
    </article>
  </div>
</section>

<section class="band" id="news">
  <div class="section-top">
    <div>
      <p class="eyebrow">Recent highlights</p>
      <h2>News and selected activities</h2>
    </div>
  </div>
  <div class="project-grid">
    <article class="project">
      <span class="number">AICHE</span>
      <h3>Conference presentation</h3>
      <p>Presented research at an AIChE-related event highlighting AI-guided nanobiosensor discovery and sequence-based design strategies.</p>
    </article>
    <article class="project">
      <span class="number">EPFL</span>
      <h3>Nanobiosensor platform</h3>
      <p>Developed a closed-loop discovery workflow that reduced the sensor development cycle from years to months.</p>
    </article>
    <article class="project">
      <span class="number">2025</span>
      <h3>Research momentum</h3>
      <p>Continuing work on the design, optimization, and translation of DNA-nanotube sensors for health-related applications.</p>
    </article>
    <article class="project">
      <span class="number">Papers</span>
      <h3>Publications</h3>
      <p>New work spans glucose sensing, nitric oxide detection, biomarker engineering, and machine learning for nanomaterial design.</p>
    </article>
  </div>
</section>

<section class="band">
  <p class="eyebrow">Research foundation</p>
  <h2>From molecular design to functional sensing</h2>
  <p class="lead">My research connects chemical engineering, materials science, and machine learning to discover responsive systems with measurable, real-world function. By combining sequence design, nanoscale materials, and automated experiments, I aim to build tools that help us detect disease biomarkers, study molecular interactions, and accelerate scientific discovery.</p>
</section>
