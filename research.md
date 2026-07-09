---
layout: default
title: Ian Moore
---

<p align="center">
  <a href="./index.html">Home</a> | 
  <strong>Research</strong> | 
  <a href="./conferences.html">Conferences</a> | 
  <a href="./teaching.html">Teaching</a> | 
  <a href="./contact.html">Contact</a>
</p>

---

# Research

My research is broadly in scientific computing, with particular application to reduced order modeling (particularly of fluids), data-driven modeling (including scientific machine learning), numerical analysis and domain decomposition. My work fixes problems with stability and extensisibility of typical reduced order models. 

# Publications

## Journal Publications

1. **Reyes, Jorge, Ping-Hsuan Tsai, Ian Moore, Honghu Liu, and Traian Iliescu.** "Verifiability and Limit Consistency of Eddy Viscosity Large Eddy Simulation Reduced Order Models." *Journal of Scientific Computing*, vol. 105, no. 3, 2025, p. 78.  
   <a href="https://doi.org/10.1007/s10915-025-03106-6" target="_blank" style="padding: 2px 8px; background-color: #007acc; color: white; border-radius: 4px; text-decoration: none; font-size: 0.85em;">DOI</a>
   <details>
     <summary style="cursor: pointer; color: #555; font-size: 0.9em; margin-top: 5px;">Show Abstract</summary>
     <p style="font-size: 0.9em; color: #444; padding-left: 10px; border-left: 2px solid #ccc; margin-top: 5px;">
       Large eddy simulation reduced order models (LES-ROMs) are ROMs that leverage LES ideas (e.g., filtering and closure modeling) to construct accurate and efficient ROMs for convection-dominated (e.g., turbulent) flows. Eddy viscosity (EV) ROMs (e.g., Smagorinsky ROM (S-ROM)) are LES-ROMs whose closure model consists of a diffusion-like operator in which the viscosity depends on the ROM velocity. We propose the Ladyzhenskaya ROM (L-ROM), which is a generalization of the S-ROM. Furthermore, we prove two fundamental numerical analysis results for the new L-ROM and the classical S-ROM: (i) We prove the verifiability of the L-ROM and S-ROM, i.e., that the ROM error is bounded (up to a constant) by the ROM closure error. (ii) We introduce the concept of ROM limit consistency (in a discrete sense), and prove that the L-ROM and S-ROM are limit consistent, i.e., that as the ROM dimension approaches the rank of the snapshot matrix, d, and the ROM lengthscale goes to zero, the ROM solution converges to the "true solution", i.e., the solution of the d-dimensional ROM. Finally, we illustrate numerically the verifiability and limit consistency of the new L-ROM and S-ROM in two under-resolved convection-dominated problems that display sharp gradients: (i) the 1D Burgers equation with a small diffusion coefficient; and (ii) the 2D lid-driven cavity flow at Reynolds number $Re=15,000$.
     </p>
   </details>

2. **Ian Moore, Anna Sanfilippo, Francesco Ballarin, and Traian Iliescu.** "A Priori Error Bounds for the Approximate Deconvolution Leray Reduced Order Model." *Numerical Methods for Partial Differential Equations*, vol. 41, no. 6, 2025, p. e70044.  
   <a href="https://doi.org/10.1002/num.70044" target="_blank" style="padding: 2px 8px; background-color: #007acc; color: white; border-radius: 4px; text-decoration: none; font-size: 0.85em;">DOI</a>
   <details>
     <summary style="cursor: pointer; color: #555; font-size: 0.9em; margin-top: 5px;">Show Abstract</summary>
     <p style="font-size: 0.9em; color: #444; padding-left: 10px; border-left: 2px solid #ccc; margin-top: 5px;">
       The approximate deconvolution Leray reduced order model (ADL-ROM) uses spatial filtering to increase the ROM stability, and approximate deconvolution to increase the ROM accuracy. In the under-resolved numerical simulation of convection-dominated flows, ADL-ROM was shown to be significantly more stable than the standard ROM and more accurate than the Leray ROM. In this paper, we equip ADL-ROM with a new van Cittert AD operator and prove a priori error bounds for both the AD operator and the ADL-ROM. To our knowledge, these are the first numerical analysis results for approximate deconvolution in a ROM context. We illustrate these numerical analysis results in the numerical simulation of convection-dominated flows.
     </p>
   </details>

3. **Sanfilippo, Anna, Ian Moore, Francesco Ballarin, and Traian Iliescu.** "Approximate deconvolution Leray reduced order model for convection-dominated flows." *Finite Elements in Analysis and Design*, vol. 226, 2023, p. 104021.  
   <a href="https://doi.org/10.1016/j.finel.2023.104021" target="_blank" style="padding: 2px 8px; background-color: #007acc; color: white; border-radius: 4px; text-decoration: none; font-size: 0.85em;">DOI</a>
   <details>
     <summary style="cursor: pointer; color: #555; font-size: 0.9em; margin-top: 5px;">Show Abstract</summary>
     <p style="font-size: 0.9em; color: #444; padding-left: 10px; border-left: 2px solid #ccc; margin-top: 5px;">
       In this paper, we propose a novel ROM stabilization strategy for under-resolved convection-dominated flows, the approximate deconvolution Leray ROM (ADL-ROM). The new ADL-ROM introduces AD as a new means to increase the accuracy of the classical Leray ROM (L-ROM) without degrading its numerical stability. We also introduce two new AD ROM strategies: the Tikhonov and van Cittert methods. Our numerical investigation for convection-dominated systems shows that, when the filter radius is relatively large, the new ADL-ROM is more accurate than the standard L-ROM. Furthermore, the new ADL-ROM is less sensitive with respect to model parameters than L-ROM.
     </p>
   </details>

---

## Preprints

4. **Tezaur, I., E. Parish, A. Gruber, I. Moore, C. R. Wentland, and I. Mota.** "Hybrid coupling with operator inference and the overlapping Schwarz alternating method." *arXiv preprint*, 2025.  
   <a href="https://arxiv.org/abs/2511.20687" target="_blank" style="padding: 2px 8px; background-color: #b31b1b; color: white; border-radius: 4px; text-decoration: none; font-size: 0.85em;">arXiv</a>

5. **Moore, I., C. R. Wentland, A. Gruber, and I. Tezaur.** "Domain Decomposition-Based Coupling of High-Fidelity Finite Element and Reduced Order Operator Inference Models Using the Schwarz Alternating Method." *arXiv preprint*, 2025.  
   <a href="https://arxiv.org/abs/2510.05350" target="_blank" style="padding: 2px 8px; background-color: #b31b1b; color: white; border-radius: 4px; text-decoration: none; font-size: 0.85em;">arXiv</a>

---

## Other Publications

6. **Moore, I., C. R. Wentland, A. Gruber, and I. Tezaur.** "Domain Decomposition-Based Coupling of Operator Inference Reduced Order Models via the Schwarz Alternating Method." *Computer Science Research Institute Summer Proceedings*, Sandia National Laboratories, 2024, pp. 109-127.  
   <a href="https://arxiv.org/abs/2409.01433" target="_blank" style="padding: 2px 8px; background-color: #b31b1b; color: white; border-radius: 4px; text-decoration: none; font-size: 0.85em;">arXiv</a>

7. **Moore, I.** "Filter Based Stabilization Methods for Reduced Order Models of Convection-Dominated Systems." *M.S. Thesis*, Virginia Tech, 2023.  
   <span style="padding: 2px 8px; background-color: #6e6e6e; color: white; border-radius: 4px; font-size: 0.85em;">M.S. Thesis</span>