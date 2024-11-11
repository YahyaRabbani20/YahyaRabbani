---
layout: "single"
title: "Research and Publications"
permalink: "/research/"
author_profile: true
---

<script type="text/javascript">
   function toggleVisibility(block_id) {
       var e = document.getElementById(block_id);
       if(e.style.display == 'block')
          e.style.display = 'none';
       else
          e.style.display = 'block';
   }
    function copyToClip(element) {
        var str = document.getElementById(element).innerHTML;
        function listener(e) {
            e.clipboardData.setData("text/html", str);
            e.clipboardData.setData("text/plain", str);
            e.preventDefault();
        }
        document.addEventListener("copy", listener);
        document.execCommand("copy");
        document.removeEventListener("copy", listener);
};
</script>

# Publications

For a complete list of publications, please refer to my [Google Scholar](https://scholar.google.co.in/citations?user=gk2vj4YAAAAJ&hl=en) page.

## Patents and Books
- **Optimizing optical nano-biosensors** for detecting molecules such as glucose and cancer biomarkers, developed with single-walled carbon nanotubes wrapped in single-stranded DNA sequences.
  *Patent under process at EPFL (P193835EP00)*

- **Sustainable Magnetorheological Fluid Synthesis** with Proper Rheological Properties for Industrial Applications.
  *Iranian Patent 98516*

- **Process Optimization in Chemical Engineering**, Iran University of Science and Technology  
  *Published Book*

- **Engineering the Properties of Nanobiooptical Sensors**  
  *Chapter in progress*

## Selected Journal Publications
### Under review 
- **Designing ssDNA-SWCNT Nano biosensors for Small Molecule Glucose Detection Using Clustering and Deep Learning**  
  *Yahya Rabbani, et al.*  
- **A new clustering approach for engineering ssDNA-SWCNT sensor for OPG cancer biomarker detection**  
  *Yahya Rabbani, et al.*  
- **Machine Learning Engineering of ssDNA-SWCNT Sensor for Nitric Oxide Detection**  
  *Yahya Rabbani, et al.*  
### 2023
- **Prediction of mycotoxin response of DNA-wrapped nanotube sensor with machine learning**  
  *Yahya Rabbani, et al.*  
  Published in *bioRxiv*  

### 2017
- **Application of artificial neural networks and support vector regression modeling in prediction of magnetorheological fluid rheometery**  
  *Yahya Rabbani, et al.*  
  Published in *Colloids and Surfaces A: Physicochemical and Engineering Aspects*  


## Additional Publications
- Investigation of the effect of parameters on hydrophobic carbonyl nanostructures with glucose and silane coating, *Ceramics International*
- Experimental Study on Magnetorheological Fluid Stability and MR Effect, *Soft Matter Journal*
- Application of Neural Networks and Support Vector Regression for Magnetorheological Fluid Rheometry, *Colloids and Surfaces A*
- Superhydrophobicity of carbonyl iron/SiO₂ particles for oil/water separation, *Scientific Reports*, Nature

---
# Projects

## Process Optimization and Simulation in Chemical Engineering

This section provides a summary of my experience in simulation and optimization within chemical engineering. Throughout my academic and professional career, I have focused on enhancing chemical processes and computational models, using tools such as **MATLAB**, **Aspen HYSYS**, **ANSYS Fluent**, **OpenFOAM**, and **LIGGGHTS**.

Key areas include:

1. **Computational Fluid Dynamics (CFD)**: Applying CFD techniques for fluid flow and heat transfer simulations, I have worked on projects such as two-phase fluid systems and solar chimney energy generation, optimizing parameters like flow rates and thermal conductivity.

2. **Process Optimization**: With **Aspen HYSYS**, I have conducted process simulations to optimize distillation columns, reactors, and heat exchangers, enhancing yields and reducing energy consumption across various plant systems.

3. **CFD-DEM Coupling**: Combining CFD (using **OpenFOAM**) with DEM (using **LIGGGHTS**), I explored the behavior of magnetorheological fluids, focusing on fluid-particle interactions under magnetic fields. This research, including work from my master’s thesis, contributed to understanding shear and dynamic yield stress properties in such fluids.

This summary reflects my commitment to advancing chemical engineering through computational methods and simulation tools. Please feel free to reach out if you are interested in collaboration on related projects.

---
## Rheological Fluid Behavior Using Neural Network Modeling (2014-2016)

During my master's research from 2014 to 2016, I applied **Artificial Neural Networks (ANN)** and **Support Vector Regression (SVR)** to model and predict the rheological properties of magnetorheological fluids (MRF) under various conditions, including shear stress, shear rate, temperature, and magnetic field strengths. The models aimed to address challenges in predicting fluid behavior at low shear rates where traditional methods underperformed, providing insights into fluid dynamics and rheology for MRFs.
The primary objective was to use machine learning techniques to capture the complex behavior of MRFs, specifically focusing on properties like shear stress and dynamic yield stress under low shear conditions. Due to limitations in rheometry instruments for accurately measuring low shear rates, the ANN model successfully estimated these properties, offering reliable predictions where conventional tools fell short.

### Technologies and Tools Used
- **MATLAB**: Employed for developing and training **ANN** and **SVR** models, enabling accurate predictions based on experimental data and simulations, especially under challenging low shear rate conditions.

### Key Project Highlights

1. **ANN and SVR Models for Rheology Prediction**:
   - **Artificial Neural Networks (ANN)**: Used to model the fluid's nonlinear behavior under various temperatures and magnetic field strengths.
   - **Support Vector Regression (SVR)**: Enhanced prediction accuracy for dynamic yield stress at low shear rates.
   - **Parameter Sensitivity Analysis**: Conducted to assess how different factors, including magnetic field strength, particle concentration, and temperature, impact MRF properties.

2. **Teaching Assistant Experience in Optimization Algorithms**:
   As a **Teaching Assistant** for "Optimization of Chemical Engineering Processes" at **Iran University of Science and Technology (IUST)**, I guided students through various optimization techniques, covering **heuristic** and **meta-heuristic** algorithms with practical applications in chemical engineering.

   - **Heuristic Algorithms**: Practical, problem-specific techniques like **Gradient Descent** were taught to tackle optimization challenges in engineering.
   - **Meta-Heuristic Algorithms**: Covered strategies such as **Genetic Algorithms (GA)** and **Bee Colony Optimization** to help students explore complex search spaces for near-optimal solutions. These were applied to real-world scenarios, including reactor optimization, energy minimization, and process yield improvement.

### Paper Reference
This project is detailed in my publication:

**"Application of Artificial Neural Networks and Support Vector Regression Modeling in Prediction of Magnetorheological Fluid Rheometry"**, published in *Colloids and Surfaces A: Physicochemical and Engineering Aspects*. The paper delves into the use of **ANN** and **SVR** to predict MRF behavior across varying conditions, emphasizing the model’s effectiveness at low shear rates.

- Access the paper [here](https://www.sciencedirect.com/science/article/pii/S0927775717301176?via%3Dihub).
