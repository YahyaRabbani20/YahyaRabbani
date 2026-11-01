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

<p class="statement">I engineer <strong>DNA-wrapped single-walled carbon nanotube (ssDNA–SWCNT) sensors</strong>, whose <strong>near-infrared fluorescence</strong> changes when a target molecule interacts with the DNA–nanotube interface. Because the DNA sequence decides what the sensor responds to, I combine <strong>sequence clustering</strong>, <strong>high-throughput screening</strong>, and <strong>deep learning</strong> to search a design space of roughly 10<sup>18</sup> sequences — and have applied this platform to four very different targets.</p>

<div class="study" id="glucose">
  <span class="tag">01 / Glucose</span>
  <h2>Non-enzymatic optical glucose sensing</h2>
  <p>Glucose monitoring is central to diabetes management, but today's continuous sensors rely on <strong>enzymes</strong> whose by-products are inflammatory and toxic. DNA–nanotube sensors offer an <strong>enzyme-free optical alternative</strong> — yet earlier approaches had not found a DNA sequence that makes them respond to glucose.</p>
  <p>I designed a <strong>diverse library of 90 DNA sequences by clustering</strong> (sequence similarity, k-mer motifs, and predicted folding), screened it by near-infrared fluorescence in 384-well plates, and improved the most responsive sequence through <strong>mutations prioritized by deep learning and pattern recognition</strong>. The mutation and ML-guided rounds shifted responses upward relative to clustering alone, yielding <strong>glucose-responsive DNA–nanotube sensors</strong> with concentration-dependent changes in both fluorescence intensity and emission wavelength, and a response that persists in 10% serum.</p>
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
We selected 48 experimental candidates from a computational library of one million DNA sequences using complementary sequence representations. Iterative mutation, clustering, and screening identified variants with larger OPG-induced peak shifts and improved discrimination against BSA under the tested conditions.

Screening data also supported neural-network training to identify additional high-response candidates. This combines exploration of sequence diversity with experimental selection.

**Key distinction:** An increased response to OPG and discrimination against BSA are experimental findings; clinical diagnostic performance remains a separate validation task.

*Manuscript in submission.*

## Nitric oxide sensing {#nitric-oxide}
Sequence representations, pattern recognition, and machine learning guide the selection of DNA–nanotube sensors with high fluorescence brightness and strong nitric-oxide responses. Optical screening connects sequence-dependent behavior to measured fluorescence quenching.

This work supports sensor development toward inflammation monitoring; future studies will assess performance in complex biological samples.

[View related publications on Google Scholar](https://scholar.google.com/citations?user=gk2vj4YAAAAJ&hl=en)

## Predictive sequence selection for fumonisin B1 {#mycotoxin}
Machine learning classifies DNA–nanotube sensor responses to the mycotoxin fumonisin B1 and guides the selection of mutated and dissimilar DNA sequences for experimental testing. The work connects model predictions with measured optical responses toward food-safety sensing.

[Read the mycotoxin preprint on bioRxiv](https://doi.org/10.1101/2023.09.07.556334)

## A broader chemical engineering foundation
My earlier work spans magnetorheological materials, experimental rheology, neural-network and support-vector-regression models, computational fluid dynamics, and process optimization. These foundations inform my current approach to linking material behavior, predictive models, and experiments.

[Browse my full publication record on Google Scholar ↗](https://scholar.google.com/citations?user=gk2vj4YAAAAJ&hl=en)
