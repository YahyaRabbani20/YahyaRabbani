---
layout: portfolio
title: "Publications"
permalink: /publications/
hide_title: true
wide: true
excerpt: "Publications, patents, and books by Yahya Rabbani on AI-guided nanobiosensors, magnetorheological fluids, functional materials, and bioprocess engineering."
---

<section class="page-banner">
  <h1>Publications</h1>
  <p class="keywords">Chemical engineering<span>|</span>Machine learning<span>|</span>Experimental nanobiotechnology<span>|</span>Nanobiosensors</p>
</section>

<p class="pub-intro">For my complete and up-to-date publication record, please see my <a href="https://scholar.google.com/citations?user=gk2vj4YAAAAJ&amp;hl=en" target="_blank" rel="noopener">Google Scholar page</a>.</p>

<div class="pub-filter" role="group" aria-label="Filter publications by topic">
  <button type="button" data-filter="all" aria-pressed="true">All Papers</button>
  <button type="button" data-filter="ai-bio" aria-pressed="false">AI &amp; Biosensors</button>
  <button type="button" data-filter="surf" aria-pressed="false">Functional Materials</button>
  <button type="button" data-filter="bio" aria-pressed="false">AI, Modeling &amp; Experimental Design</button>
</div>
<p class="pub-count" id="pub-count" aria-live="polite"></p>

<div id="pub-list">
<article class="pub-card" data-cat="ai-bio">
  <div class="pub-thumb"><img src="{{ '/images/Image_P2a.png' | relative_url }}" alt="" loading="lazy"></div>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">A new clustering approach for the engineering of the ssDNA-SWCNT sensor for OPG cancer biomarker detection</span> <span class="badge">In submission</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>‡, S. Behjati‡, B. Rousseau, S. H. Sajjadi, N. Sharif, A. A. Boghossian</span></p>
    <p><span class="lbl">Status</span>Manuscript</p>
    
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  <div class="pub-thumb"><img src="{{ '/images/Image_P3a.png' | relative_url }}" alt="" loading="lazy"></div>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Machine learning engineering of ssDNA-SWCNT sensors for nitric oxide detection</span> <span class="badge">In submission</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, S. H. Sajjadi, S. Behjati, N. Sharif, A. A. Boghossian</span></p>
    <p><span class="lbl">Status</span>Manuscript</p>
    
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  {% assign th = site.static_files | where: "path", "/images/hybridization.png" | first %}{% if th %}<div class="pub-thumb"><img src="{{ '/images/hybridization.png' | relative_url }}" alt="" loading="lazy"></div>{% else %}<div class="pub-thumb ph"><b>DNA on carbon nanotubes</b><span>In preparation</span></div>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Machine learning engineering of ssDNA hybridization on the surface of SWCNTs</span> <span class="badge">In preparation</span></p>
    <p><span class="lbl">Authors</span><span class="auth">B. Rousseau, <strong>Y. Rabbani</strong>, A. A. Boghossian</span></p>
    <p><span class="lbl">Status</span>Manuscript</p>
    
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  <a class="pub-thumb" href="https://www.sciencedirect.com/science/article/pii/S0956566325009698" target="_blank" rel="noopener"><img src="https://ars.els-cdn.com/content/image/1-s2.0-S0956566325009698-gr1.jpg" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Single-walled carbon nanotube biosensor for real-time monitoring of nitric oxide in inflammatory responses</span></p>
    <p><span class="lbl">Authors</span><span class="auth">V. Zubkovs, L. Belcastro, S. H. Sajjadi, <strong>Y. Rabbani</strong>, A. Rastiniemi, …, S. Cattaneo, A. A. Boghossian, V. Basoli</span></p>
    <p><span class="lbl">Journal</span><em>Biosensors and Bioelectronics</em>, 293, 118092, 2026</p>
    <a class="read-btn" href="https://www.sciencedirect.com/science/article/pii/S0956566325009698" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  <a class="pub-thumb" href="https://www.biorxiv.org/content/10.1101/2025.05.06.652529v1" target="_blank" rel="noopener"><img src="https://raw.githubusercontent.com/YahyaRabbani20/AI-BioSense/main/images/GraphicalAbstract.jpg" alt="" loading="lazy"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Discovery of a DNA-based optical nanotube sensor for glucose using clustering and deep learning algorithms</span> <span class="badge">Preprint</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, J. Bregy, B. Rousseau, S. H. Sajjadi, L. De Benedittis, S. Behjati, M. Mouhib, S. Dehury, A. A. Boghossian</span></p>
    <p><span class="lbl">Journal</span><em>bioRxiv</em>, 2025</p>
    <a class="read-btn" href="https://www.biorxiv.org/content/10.1101/2025.05.06.652529v1" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  {% assign th = site.static_files | where: "path", "/images/ecs-2025.png" | first %}{% if th %}<a class="pub-thumb" href="https://iopscience.iop.org/article/10.1149/2.F15254IF" target="_blank" rel="noopener"><img src="{{ '/images/ecs-2025.png' | relative_url }}" alt="" loading="lazy"></a>{% else %}<a class="pub-thumb ph" href="https://iopscience.iop.org/article/10.1149/2.F15254IF" target="_blank" rel="noopener"><b>ECS Interface</b><span>2025</span></a>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Advancements in the surface functionalization of carbon nanotubes for optoelectronic modulation and sensing applications</span> <span class="badge">Featured article</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, A. A. Boghossian</span></p>
    <p><span class="lbl">Journal</span><em>The Electrochemical Society Interface</em>, 2025</p>
    <a class="read-btn" href="https://iopscience.iop.org/article/10.1149/2.F15254IF" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  {% assign th = site.static_files | where: "path", "/images/glutathione.png" | first %}{% if th %}<div class="pub-thumb"><img src="{{ '/images/glutathione.png' | relative_url }}" alt="" loading="lazy"></div>{% else %}<div class="pub-thumb ph"><b>Small Methods</b><span>2025</span></div>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Enabling pH resilience of an optical glutathione sensor by distinguishing enthalpy- and entropy-driven interactions</span> <span class="badge">Under review</span></p>
    <p><span class="lbl">Authors</span><span class="auth">S. Behjati, L. Huang, B. Rousseau, <strong>Y. Rabbani</strong>, H. Wang, S. Dehury, R. Di Costanzo, S. H. Sajjadi, D. Constam, A. A. Boghossian</span></p>
    <p><span class="lbl">Journal</span><em>Small Methods</em>, 2025</p>
    
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  {% assign th = site.static_files | where: "path", "/images/handbook.png" | first %}{% if th %}<a class="pub-thumb" href="https://www.worldscientific.com/worldscibooks/10.1142/14067" target="_blank" rel="noopener"><img src="{{ '/images/handbook.png' | relative_url }}" alt="" loading="lazy"></a>{% else %}<a class="pub-thumb ph" href="https://www.worldscientific.com/worldscibooks/10.1142/14067" target="_blank" rel="noopener"><b>Handbook of Carbon Nanomaterials</b><span>2025</span></a>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Bioengineering DNA for carbon nanotube sensors</span> <span class="badge">Book chapter</span></p>
    <p><span class="lbl">Authors</span><span class="auth">S. Behjati, <strong>Y. Rabbani</strong>, A. A. Boghossian</span></p>
    <p><span class="lbl">Book</span><em>Handbook of Carbon Nanomaterials</em>, Vol. 2, Ch. 8, 421-454, 2025</p>
    <a class="read-btn" href="https://www.worldscientific.com/worldscibooks/10.1142/14067" target="_blank" rel="noopener">View book</a>
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  <a class="pub-thumb" href="https://patents.google.com/patent/EP4742248A1/en" target="_blank" rel="noopener"><img src="{{ '/images/Image_H_All.png' | relative_url }}" alt="" loading="lazy"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Optimizing optical nano-biosensors made of single-walled carbon nanotubes wrapped in single-stranded DNA sequences for detection of molecules such as glucose and cancer biomarkers</span> <span class="badge">Patent</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong> (60%), J. Bregy, A. A. Boghossian</span></p>
    <p><span class="lbl">Patent</span>European patent EP 4742248 A1 (application EP 24211885.9), Filed 2024</p>
    <a class="read-btn" href="https://patents.google.com/patent/EP4742248A1/en" target="_blank" rel="noopener">View patent</a>
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  {% assign th = site.static_files | where: "path", "/images/bioconj-2024.png" | first %}{% if th %}<a class="pub-thumb" href="https://pubs.acs.org/doi/10.1021/acs.bioconjchem.3c00388" target="_blank" rel="noopener"><img src="{{ '/images/bioconj-2024.png' | relative_url }}" alt="" loading="lazy"></a>{% else %}<a class="pub-thumb ph" href="https://pubs.acs.org/doi/10.1021/acs.bioconjchem.3c00388" target="_blank" rel="noopener"><b>Bioconjugate Chemistry</b><span>2024</span></a>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Micropreparative gel electrophoresis for purification of nanoscale bioconjugates</span></p>
    <p><span class="lbl">Authors</span><span class="auth">S. H. Sajjadi, S. J. Wu, <strong>Y. Rabbani</strong>, V. Zubkovs, H. Ahmadzadeh, et al.</span></p>
    <p><span class="lbl">Journal</span><em>Bioconjugate Chemistry</em>, 35(2), 154-163, 2024</p>
    <a class="read-btn" href="https://pubs.acs.org/doi/10.1021/acs.bioconjchem.3c00388" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="ai-bio">
  <a class="pub-thumb" href="https://www.biorxiv.org/content/10.1101/2023.09.07.556334v1" target="_blank" rel="noopener"><img src="{{ '/images/Image_P4a.png' | relative_url }}" alt="" loading="lazy"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Prediction of mycotoxin response of DNA-wrapped nanotube sensor with machine learning</span> <span class="badge">Preprint</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, S. Behjati, B. Lambert, S. H. Sajjadi, M. Shariaty-Niassar, et al.</span></p>
    <p><span class="lbl">Journal</span><em>bioRxiv</em>, 2023</p>
    <a class="read-btn" href="https://www.biorxiv.org/content/10.1101/2023.09.07.556334v1" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="surf">
  {% assign th = site.static_files | where: "path", "/images/jimss-2023.png" | first %}{% if th %}<a class="pub-thumb" href="https://journals.sagepub.com/doi/10.1177/1045389X221147667" target="_blank" rel="noopener"><img src="{{ '/images/jimss-2023.png' | relative_url }}" alt="" loading="lazy"></a>{% else %}<a class="pub-thumb ph" href="https://journals.sagepub.com/doi/10.1177/1045389X221147667" target="_blank" rel="noopener"><b>J. Intell. Mater. Syst. Struct.</b><span>2023</span></a>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">The effect of microparticles/nanoparticles surface modification on the magnetorheological fluid properties: a review</span> <span class="badge">Review</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, N. Hajinajaf, M. Shariaty-Niassar</span></p>
    <p><span class="lbl">Journal</span><em>Journal of Intelligent Material Systems and Structures</em>, 34(15), 1715, 2023</p>
    <a class="read-btn" href="https://journals.sagepub.com/doi/10.1177/1045389X221147667" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="surf">
  <a class="pub-thumb" href="https://www.nature.com/articles/s41598-023-31770-x" target="_blank" rel="noopener"><img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1038%2Fs41598-023-31770-x/MediaObjects/41598_2023_31770_Fig6_HTML.png" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Durable superhydrophobic/superoleophilic melamine foam based on biomass-derived porous carbon and multi-walled carbon nanotube for oil/water separation</span></p>
    <p><span class="lbl">Authors</span><span class="auth">H. Shayesteh, M. S. Khosrowshahi, H. Mashhadimoslem, F. Maleki, <strong>Y. Rabbani</strong>, et al.</span></p>
    <p><span class="lbl">Journal</span><em>Scientific Reports</em>, 13, 4515, 2023</p>
    <a class="read-btn" href="https://www.nature.com/articles/s41598-023-31770-x" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="surf">
  <a class="pub-thumb" href="https://www.nature.com/articles/s41598-023-28131-z" target="_blank" rel="noopener"><img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1038%2Fs41598-023-28131-z/MediaObjects/41598_2023_28131_Fig5_HTML.png" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Investigation of grafting silane coupling agents on superhydrophobicity of carbonyl iron/SiO₂ particles for efficient oil/water mixture and emulsion separation</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, H. Shayesteh, N. Haghshenas, M. Safarzadeh Khosrowshahi</span></p>
    <p><span class="lbl">Journal</span><em>Scientific Reports</em>, 13, 788, 2023</p>
    <a class="read-btn" href="https://www.nature.com/articles/s41598-023-28131-z" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="bio">
  <a class="pub-thumb" href="https://link.springer.com/article/10.1007/s12649-022-01800-2" target="_blank" rel="noopener"><img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs12649-022-01800-2/MediaObjects/12649_2022_1800_Figa_HTML.png" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Integrated CO₂ capture and nutrient removal by microalgae Chlorella vulgaris and optimization using neural network and support vector regression</span></p>
    <p><span class="lbl">Authors</span><span class="auth">N. Hajinajaf, A. Fallahi, <strong>Y. Rabbani</strong>, O. Tavakoli, M. H. Sarrafzadeh</span></p>
    <p><span class="lbl">Journal</span><em>Waste and Biomass Valorization</em>, 13(12), 4749-4770, 2022</p>
    <a class="read-btn" href="https://link.springer.com/article/10.1007/s12649-022-01800-2" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="bio">
  <a class="pub-thumb" href="https://link.springer.com/article/10.1007/s13762-021-03760-x" target="_blank" rel="noopener"><img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs13762-021-03760-x/MediaObjects/13762_2021_3760_Fig2_HTML.png" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Experimental and modeling assessment of large-scale cultivation of microalgae Nannochloropsis sp. PTCC 6016 to reach high efficiency lipid extraction</span></p>
    <p><span class="lbl">Authors</span><span class="auth">N. Hajinajaf, <strong>Y. Rabbani</strong>, A. Mehrabadi, O. Tavakoli</span></p>
    <p><span class="lbl">Journal</span><em>International Journal of Environmental Science and Technology</em>, 19(6), 5511-5528, 2022</p>
    <a class="read-btn" href="https://link.springer.com/article/10.1007/s13762-021-03760-x" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="bio">
  <a class="pub-thumb" href="https://pubs.rsc.org/en/content/articlelanding/2022/ra/d1ra09334g" target="_blank" rel="noopener"><img src="{{ '/images/RSC_2022.png' | relative_url }}" alt="" loading="lazy"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">The optimization effect of different parameters on the super hydrophobicity of prickly-shaped carbonyl iron particles</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, M. Shariaty-Niassar, S. A. S. Ebrahimi</span></p>
    <p><span class="lbl">Journal</span><em>RSC Advances</em>, 12(20), 12760-12772, 2022</p>
    <a class="read-btn" href="https://pubs.rsc.org/en/content/articlelanding/2022/ra/d1ra09334g" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="surf">
  <a class="pub-thumb" href="https://www.sciencedirect.com/science/article/pii/S0272884221020174" target="_blank" rel="noopener"><img src="https://ars.els-cdn.com/content/image/1-s2.0-S0272884221020174-gr3.jpg" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">The effect of superhydrophobicity of prickly shape carbonyl iron particles on the oil-water adsorption</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, M. Shariaty-Niassar, S. A. S. Ebrahimi</span></p>
    <p><span class="lbl">Journal</span><em>Ceramics International</em>, 47(20), 28400-28410, 2021</p>
    <a class="read-btn" href="https://www.sciencedirect.com/science/article/pii/S0272884221020174" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="bio">
  <a class="pub-thumb" href="https://arc.aiaa.org/doi/10.2514/1.T5656" target="_blank" rel="noopener"><img src="{{ '/images/JTHT_2020.png' | relative_url }}" alt="" loading="lazy"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Investigation of the chain formation effect on thermal conductivity of magnetorheological fluids</span></p>
    <p><span class="lbl">Authors</span><span class="auth">J. Maroofi, S. H. Hashemabadi, <strong>Y. Rabbani</strong></span></p>
    <p><span class="lbl">Journal</span><em>Journal of Thermophysics and Heat Transfer</em>, 34(1), 3-12, 2020</p>
    <a class="read-btn" href="https://arc.aiaa.org/doi/10.2514/1.T5656" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="bio">
  {% assign th = site.static_files | where: "path", "/images/book.png" | first %}{% if th %}<div class="pub-thumb"><img src="{{ '/images/book.png' | relative_url }}" alt="" loading="lazy"></div>{% else %}<div class="pub-thumb ph"><b>Process Optimization</b><span>2020</span></div>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Process optimization in chemical engineering</span> <span class="badge">Book</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, S. M. Sadeghi</span></p>
    <p><span class="lbl">Book</span>Published 2020</p>
    
  </div>
</article>
<article class="pub-card" data-cat="surf">
  <a class="pub-thumb" href="https://link.springer.com/article/10.1007/s10973-018-7538-7" target="_blank" rel="noopener"><img src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs10973-018-7538-7/MediaObjects/10973_2018_7538_Fig4_HTML.jpg" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">An experimental study on stability and rheological properties of magnetorheological fluid using iron nanoparticle core-shell structured by cellulose</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, N. Hajinajaf, O. Tavakoli</span></p>
    <p><span class="lbl">Journal</span><em>Journal of Thermal Analysis and Calorimetry</em>, 135, 1687-1697, 2019</p>
    <a class="read-btn" href="https://link.springer.com/article/10.1007/s10973-018-7538-7" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="surf bio">
  <a class="pub-thumb" href="https://www.sciencedirect.com/science/article/pii/S0927775717301176" target="_blank" rel="noopener"><img src="https://ars.els-cdn.com/content/image/1-s2.0-S0927775717301176-fx1.jpg" alt="" loading="lazy" referrerpolicy="no-referrer"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Application of artificial neural networks and support vector regression modeling in prediction of magnetorheological fluid rheometry</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, M. Shirvani, S. H. Hashemabadi, M. Keshavarz</span></p>
    <p><span class="lbl">Journal</span><em>Colloids and Surfaces A</em>, 520, 268-278, 2017</p>
    <a class="read-btn" href="https://www.sciencedirect.com/science/article/pii/S0927775717301176" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
<article class="pub-card" data-cat="surf">
  {% assign th = site.static_files | where: "path", "/images/iran-patent.png" | first %}{% if th %}<div class="pub-thumb"><img src="{{ '/images/iran-patent.png' | relative_url }}" alt="" loading="lazy"></div>{% else %}<div class="pub-thumb ph"><b>Iranian Patent</b><span>2017</span></div>{% endif %}
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">Sustainable magnetorheological fluid synthesis with proper rheological properties for industrial applications using nanoparticles and stabilizing additives</span> <span class="badge">Patent</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong> (80%), A. Hamta</span></p>
    <p><span class="lbl">Patent</span>Iranian Patent No. 98516, 2017</p>
    
  </div>
</article>
<article class="pub-card" data-cat="surf">
  <a class="pub-thumb" href="https://pubs.rsc.org/en/content/articlelanding/2015/sm/c5sm00625b" target="_blank" rel="noopener"><img src="{{ '/images/SoftMatter_2015.png' | relative_url }}" alt="" loading="lazy"></a>
  <div class="pub-meta">
    <p><span class="lbl">Title</span><span class="ttl">An experimental study on the effects of temperature and magnetic field strength on the magnetorheological fluid stability and MR effect</span></p>
    <p><span class="lbl">Authors</span><span class="auth"><strong>Y. Rabbani</strong>, M. Ashtiani, S. H. Hashemabadi</span></p>
    <p><span class="lbl">Journal</span><em>Soft Matter</em>, 11(22), 4453-4460, 2015</p>
    <a class="read-btn" href="https://pubs.rsc.org/en/content/articlelanding/2015/sm/c5sm00625b" target="_blank" rel="noopener">Read paper</a>
  </div>
</article>
</div>

<p class="pub-note">‡ Equal contribution.</p>

<script>
(function () {
  var buttons = Array.prototype.slice.call(document.querySelectorAll('.pub-filter button'));
  var cards = Array.prototype.slice.call(document.querySelectorAll('.pub-card'));
  var count = document.getElementById('pub-count');
  function apply(f) {
    var n = 0;
    cards.forEach(function (c) {
      var show = f === 'all' || (' ' + c.getAttribute('data-cat') + ' ').indexOf(' ' + f + ' ') > -1;
      c.classList.toggle('is-hidden', !show);
      if (show) n++;
    });
    buttons.forEach(function (b) { b.setAttribute('aria-pressed', b.getAttribute('data-filter') === f ? 'true' : 'false'); });
    count.textContent = 'Showing ' + n + (n === 1 ? ' item' : ' items');
  }
  buttons.forEach(function (b) { b.addEventListener('click', function () { apply(b.getAttribute('data-filter')); }); });
  apply('all');
})();
</script>
