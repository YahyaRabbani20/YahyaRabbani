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

<div class="study" id="opg">
  <span class="tag">02 / OPG protein</span>
  <h2>Clustering-assisted directed evolution for OPG sensing</h2>
  <p>Osteoprotegerin (OPG) is a <strong>protein cancer biomarker</strong>. Detecting a protein optically is hard because blood is full of other proteins, so a useful sensor must respond to OPG <strong>without responding to everything else</strong>.</p>
  <p>I selected 48 experimental candidates from a <strong>computational library of one million DNA sequences</strong> using complementary sequence representations, then ran <strong>iterative rounds of mutation, clustering, and screening</strong>. Across three generations, the OPG-induced peak shift of the (7,6) nanotube grew from about 1.1 nm to 2.2–2.8 nm, while the response to the control protein BSA stayed between roughly 1 and 1.5 nm — <strong>a stronger and more selective response</strong> under the tested conditions. The screening data also trained neural networks that nominated additional high-response candidates.</p>
  <p class="approach">Library of 10<sup>6</sup> sequences → 48 cluster-selected candidates → mutation and re-clustering over three generations → deep-learning prediction</p>
  <p class="note">Manuscript in submission. Clinical diagnostic performance has not yet been established and requires dedicated validation.</p>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P2a.png' | relative_url }}" alt="Bar chart of (7,6) peak shift for OPG and BSA across three generations for families OPGM10 and OPGM14" loading="lazy">
      <figcaption><b>(a)</b> Peak shift of the (7,6) nanotube toward OPG and the control protein BSA across three generations of directed evolution, for two sequence families (OPGM10, OPGM14).</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P2b.png' | relative_url }}" alt="Heatmap of peak-shift responses across cluster-selected DNA variants" loading="lazy">
      <figcaption><b>(b)</b> Peak-shift response patterns across cluster-selected DNA variants.</figcaption>
    </figure>
  </div>
</div>

<div class="study" id="nitric-oxide">
  <span class="tag">03 / Nitric oxide</span>
  <h2>Learning sequence–response relationships for nitric oxide</h2>
  <p>Nitric oxide (NO) is a short-lived signaling molecule at the center of <strong>inflammation</strong>, which makes it valuable to monitor and difficult to measure. A good NO sensor has to be two things at once: <strong>bright</strong> enough to read, and <strong>strongly quenched</strong> when NO is present.</p>
  <p>I combined <strong>sequence representations, pattern recognition, and machine learning</strong> to map which bases at which positions are associated with NO-induced quenching, and used those patterns to select new sequences. Sequences chosen by <strong>ML prediction concentrated in the bright, strongly quenched region</strong> (about 85–92% quenching), compared with sequences chosen by clustering alone — toward sensors for inflammation monitoring.</p>
  <p class="approach">Clustering → position and motif analysis → ML-guided sequence selection → brightness and quenching screening</p>
  <p class="note">Manuscript in submission. Related work: Zubkovs et al., <em>Biosensors and Bioelectronics</em> 293, 118092 (2026), an electronics-free optical sensor for nitric oxide in inflammatory responses.</p>
  <div class="pub-links">
    <a href="{{ '/publications/' | relative_url }}">Publications</a>
  </div>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P3a.png' | relative_url }}" alt="3D surface of mean quenching response by DNA position and base" loading="lazy">
      <figcaption><b>(a)</b> Sequence-position patterns associated with NO-induced fluorescence quenching: mean response by base (A, C, G, T) at each position.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P3b.png' | relative_url }}" alt="Scatter plot of NO-induced quenching versus PL intensity for clustering, pattern recognition, and ML prediction" loading="lazy">
      <figcaption><b>(b)</b> Sensor brightness (PL intensity) versus NO-induced quenching for sequences selected by clustering, pattern recognition, and ML prediction.</figcaption>
    </figure>
  </div>
</div>

<div class="study" id="mycotoxin">
  <span class="tag">04 / Mycotoxins</span>
  <h2>Predictive sequence selection for fumonisin B1</h2>
  <p>Fumonisin B1 (FB1) is a <strong>mycotoxin that contaminates corn</strong> and corn-based food. Current analytical methods are accurate but slow, expensive, and lab-bound, which motivates <strong>fast optical sensors</strong> — if the right DNA sequence can be found.</p>
  <p>I trained <strong>supervised models — artificial neural networks and support vector machines —</strong> on measured responses of DNA–nanotube sensors to FB1, classifying sequences as high or low responders (1.5 nm peak-shift threshold) with <strong>accuracy above 80%</strong>. The models were then used to predict <strong>new mutants and entirely dissimilar DNA sequences</strong>, which were tested experimentally to check whether the predictions held beyond the training data.</p>
  <p class="approach">Experimental training set → ANN and SVM classification with cross-validation → prediction of mutants and dissimilar sequences → experimental validation</p>
  <div class="pub-links">
    <a href="https://doi.org/10.1101/2023.09.07.556334">Preprint</a>
    <a href="https://github.com/YahyaRabbani20/ML-Models-Opticalsensor-Mycotoxin-Detection">Code</a>
  </div>
  <div class="fig-row">
    <figure>
      <img src="{{ '/images/Image_P4a.png' | relative_url }}" alt="Measured peak-shift responses of DNA sequences with predicted probability of high response shown by marker size" loading="lazy">
      <figcaption><b>(a)</b> Measured peak-shift responses with the model-predicted probability of a high response (marker size); the dashed line marks the 1.5 nm threshold.</figcaption>
    </figure>
    <figure>
      <img src="{{ '/images/Image_P4b.png' | relative_url }}" alt="Experimental responses for the training set, predicted mutants, and dissimilar DNA sequences, marking classifications and misclassifications" loading="lazy">
      <figcaption><b>(b)</b> Experimental validation across the training set, predicted mutants, and dissimilar DNA sequences, with correct classifications and misclassifications marked.</figcaption>
    </figure>
  </div>
</div>

## A broader chemical engineering foundation
My earlier work spans magnetorheological materials, experimental rheology, neural-network and support-vector-regression models, computational fluid dynamics, and process optimization. These foundational skills support my experimental design, sensing, and machine-learning approach to DNA–nanotube optical systems.

[Browse my full publication record on Google Scholar ↗](https://scholar.google.com/citations?user=gk2vj4YAAAAJ&hl=en)
