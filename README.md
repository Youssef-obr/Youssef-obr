# Hi, I’m a second-year student at IMT Atlantique interested in Machine Learning research 👋

I’m interested in **Machine Learning, scientific machine learning, applied mathematics, optimization, and modeling**.  
Below are a few projects I’ve developed mainly in **Python**.

---

## Projects

### Classical ML Surrogates for the 1D Burgers Equation

Applied several classical ML methods to learn the time evolution of the viscous Burgers equation directly from spatial grid states.

- Compared Ridge, Polynomial Ridge, RBF Kernel Ridge, and residual-correction methods.
- Evaluated both one-step prediction and recursive rollout.
- Studied prediction error, rollout stability, and computational speed compared with the numerical PDE solver.

**Keywords:** machine learning, PDE surrogates, kernel methods, regression, scientific machine learning

[View Repository](https://github.com/Youssef-obr/pde-surrogate-learning)

---

### Structured Extrema Errors in Classical Surrogates for Viscous Burgers: A Physics-Consistent Interpretation

Research project studying the structured prediction errors of ML surrogates for the viscous Burgers equation.

- Compared Kernel Ridge, Ridge, ExtraTrees, and Random Forests.
- Studied why large errors appear near extrema and their relation to curvature and viscous diffusion.
- Developed physics-based diagnostics and tested whether the identified error structure can be used to improve one-step prediction and recursive rollout.

**Keywords:** machine learning, scientific machine learning, PDEs, interpretability, residual analysis, physics-based modeling

*Repository coming soon.*

---

### No-Show Prediction Model (Healthcare Startup Prototype)

- Built a **no-show prediction model** for a women’s healthcare startup.
- Integrated the model into a **conversational prototype**:
  - A conversational assistant asks natural-language questions.
  - Relevant answers are mapped to model features.
  - The system outputs a **no-show probability** and a decision based on a configurable threshold.
- Optional explanation of likely contributing factors.

**Keywords:** machine learning, classification, decision thresholds

---

### 3D Reconstruction from Images — Photogrammetry

Developed a Python photogrammetry pipeline to reconstruct 3D point clouds from multiple images.

- Implemented a relative-orientation approach using SIFT matching, RANSAC filtering, camera pose estimation and triangulation.
- Reconstructed several real scenes, including a pyramid, stairs and a topographic map.
- Evaluated the pyramid reconstruction after scale alignment, with an average relative error of about **2.47%**.
- Also validated the geometric pipeline with absolute orientation, which allows precise measurement, and tested LoFTR to improve matching on difficult images.

**Keywords:** photogrammetry, 3D reconstruction, relative orientation, SIFT, RANSAC, LoFTR, triangulation

[View Repository](https://github.com/Youssef-obr/3d-reconstruction-photogrammetry.git)

---

### Thermal Simulation & CPU Geometry Optimization (TIPE)

- Developed a **thermal simulator for CPUs** based on physical heat transfer models.
- Implemented **geometric optimization of heat dissipation blocks**.
- Evaluated design choices through numerical simulations.
- Objective: improve thermal dissipation and justify results quantitatively in order to extend the lifespan of CPUs.

**Keywords:** thermal modeling, numerical simulation, optimization, physics-based modeling

[View Repository](https://github.com/Youssef-obr/CPU-Thermal-Simulation.git)

---

📫 **Contact:** youssef.oubari@imt-atlantique.net
