---
layout: portfolio
title: "Research"
permalink: /research/
hide_title: true
excerpt: "Experimental nanobiotechnology and machine learning for DNA–nanotube optical sensing."
---

<section class="page-banner">
  <p class="eyebrow">Yahya Rabbani / Research</p>
  <h1>Research</h1>
  <p class="keywords">Nanobiotechnology<span>|</span>Machine learning<span>|</span>Optical sensing<span>|</span>High-throughput experimentation</p>
</section>

<p class="statement">I engineer <strong>DNA-wrapped single-walled carbon nanotube (ssDNA–SWCNT) sensors</strong>, whose <strong>near-infrared fluorescence</strong> changes when a target molecule interacts with the DNA corona. By combining sequence design, high-throughput screening, and machine learning, I build predictive sensing platforms for small molecules, inflammatory markers, and food contaminants.</p>

<div class="study" id="glucose">
  <span class="tag">01 / Glucose</span>
  <h2>Non-enzymatic optical glucose sensing</h2>
  <p>Glucose monitoring is central to diabetes management, but today's continuous sensors rely on <strong>enzymes</strong> whose by-products are inflammatory and toxic. DNA–nanotube sensors offer an alternative: the optical signal responds directly to glucose in a label-free, non-enzymatic format with good reversibility and compatibility with wearable sensing.</p>
  <p>I designed a <strong>diverse library of 90 DNA sequences by clustering</strong> (sequence similarity, k-mer motifs, and predicted folding), screened it by near-infrared fluorescence in 384-well plates, and iteratively refined the best-performing sequences using mutation and model-guided selection. The resulting sensors were validated across concentration ranges relevant to physiologic monitoring.</p>
  <p class="approach">Clustering-based library design → 384-well NIR screening → deep-learning-guided mutation → validation</p>
  <div class="pub-links">
    <a href="https://doi.org/10.1101/2025.05.06.652529">Preprint</a>
    <a href="https://github.com/YahyaRabbani20/AI-BioSense">Code</a>
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
  </div>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P1a.png' | relative_url }}" alt="Violin plot of glucose-induced intensity change for clustering, mutation and clustering, and ML prediction" loading="lazy">
      <figcaption><b>(a)</b> Glucose-induced intensity change across three sequence-selection strategies: clustering, mutation and clustering, and ML prediction.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P1b.png' | relative_url }}" alt="Concentration-dependent intensity change and peak shift with sigmoid fits" loading="lazy">
      <figcaption><b>(b)</b> Concentration-dependent intensity change (red) and peak shift (blue), fitted with a sigmoid model.</figcaption>
    </figure>
  </div>
</div>

## Clustering-assisted directed evolution for OPG sensing {#opg}
We selected 48 experimental candidates from a computational library of one million DNA sequences using complementary sequence representations. Iterative mutation, clustering, and screening identified the most responsive sequences for oxidative product generation sensing, with strong signal modulation in response to the target analyte.

Screening data also supported neural-network training to identify additional high-response candidates. This combines exploration of sequence diversity with experimental selection.

**Key distinction:** An increased response to OPG and discrimination against BSA are experimental findings; clinical diagnostic performance remains a separate validation task.

<div class="fig-row">
  <figure>
    <img src="{{ '/images/Image_P2a.png' | relative_url }}" alt="Sequence selection and screening response for OPG sensing" loading="lazy">
    <figcaption><b>(a)</b> Sequence selection and screening response for OPG sensing, highlighting the clustering-assisted directed-evolution workflow.</figcaption>
  </figure>
  <figure>
    <img src="{{ '/images/Image_P2b.png' | relative_url }}" alt="Experimental signal response and model-guided candidate evaluation for OPG sensing" loading="lazy">
    <figcaption><b>(b)</b> Experimental signal response and model-guided candidate evaluation for OPG sensing across selected DNA sequences.</figcaption>
  </figure>
</div>

*Manuscript in submission.*

## Nitric oxide sensing {#nitric-oxide}
Sequence representations, pattern recognition, and machine learning guide the selection of DNA–nanotube sensors with high fluorescence brightness and strong nitric-oxide responses. Optical screening captures how sequence structure, binding interactions, and fluorescence behavior change with analyte exposure.

This work supports sensor development toward inflammation monitoring; future studies will assess performance in complex biological samples.

<div class="fig-row">
  <figure>
    <img src="{{ '/images/Image_P3a.png' | relative_url }}" alt="Nitric oxide sensing screening results and candidate performance" loading="lazy">
    <figcaption><b>(a)</b> Nitric oxide sensing screening results, showing fluorescence response patterns used to rank candidate sequences.</figcaption>
  </figure>
  <figure>
    <img src="{{ '/images/Image_P3b.png' | relative_url }}" alt="Nitric oxide response profiles across selected DNA–nanotube sensor candidates" loading="lazy">
    <figcaption><b>(b)</b> Nitric oxide response profiles across selected DNA–nanotube sensor candidates, illustrating sequence-dependent signal discrimination.</figcaption>
  </figure>
</div>

[View related publications on Google Scholar](https://scholar.google.com/citations?user=gk2vj4YAAAAJ&hl=en)

## Predictive sequence selection for fumonisin B1 {#mycotoxin}
Machine learning classifies DNA–nanotube sensor responses to the mycotoxin fumonisin B1 and guides the selection of mutated and dissimilar DNA sequences for experimental testing. The work connects molecular design, predictive modeling, and targeted screening to improve sequence discovery under constrained experimental budgets.

<div class="fig-row">
  <figure>
    <img src="{{ '/images/Image_P4a.png' | relative_url }}" alt="Predictive sequence selection workflow for fumonisin B1" loading="lazy">
    <figcaption><b>(a)</b> Predictive sequence selection workflow for fumonisin B1, showing the model-guided candidate ranking strategy.</figcaption>
  </figure>
  <figure>
    <img src="{{ '/images/Image_P4b.png' | relative_url }}" alt="Experimental fumonisin B1 response and selected sequence performance" loading="lazy">
    <figcaption><b>(b)</b> Experimental fumonisin B1 response and selected sequence performance, demonstrating model-informed discovery of high-response constructs.</figcaption>
  </figure>
</div>

[Read the mycotoxin preprint on bioRxiv](https://doi.org/10.1101/2023.09.07.556334)

## A broader chemical engineering foundation
My earlier work spans magnetorheological materials, experimental rheology, neural-network and support-vector-regression models, computational fluid dynamics, and process optimization. These foundational skills support my experimental design, sensing, and machine-learning approach to DNA–nanotube optical systems.

[Browse my full publication record on Google Scholar ↗](https://scholar.google.com/citations?user=gk2vj4YAAAAJ&hl=en)
