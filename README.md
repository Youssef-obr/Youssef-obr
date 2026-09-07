# Hi, I’m a second-year student at IMT Atlantique interested in Machine Learning research 👋

I’m interested in **Machine Learning, scientific machine learning, applied mathematics, optimization, and modeling**.  
Below are some of my research and technical projects, developed mainly in **Python**.

---

## Research & Projects

### Structured Extrema Errors in Classical Surrogates for Viscous Burgers: A Physics-Consistent Interpretation

**Research paper on the errors made by machine-learning surrogates for nonlinear PDE dynamics.**

- Compared several ML models, including **Kernel Ridge, Ridge, ExtraTrees, and Random Forests**, on the viscous Burgers equation.
- Identified structured prediction errors near extrema and studied their relation to **curvature and viscous diffusion**.
- Developed geometric and physics-based diagnostics to explain these errors.
- Tested the interpretation with **held-out trajectories, negative controls, spectral analysis, error correction, and recursive rollout**.
- Proposed a correction based only on predicted quantities and evaluated its effect on both one-step and long-horizon prediction.

**Status:** submitted to **XAI4Science @ NeurIPS 2026** and **ML4PS**, currently awaiting review.

**Keywords:** machine learning, scientific machine learning, PDE surrogates, interpretability, kernel methods, ensemble methods, residual analysis

*Repository coming soon.*

---

### Classical ML Surrogates for the 1D Burgers Equation

Applied a range of classical machine-learning methods to learn the time evolution of the viscous Burgers equation directly from spatial grid states.

This project was also used to strengthen and apply core ML concepts:

- Built supervised-learning datasets from numerical trajectories with **trajectory-level train/validation splitting** to avoid data leakage.
- Compared **persistence, linear Ridge, polynomial regression, RBF Kernel Ridge, and gradient-boosting residual correction**.
- Worked with **regularization, nonlinear feature mappings, kernel methods, hyperparameter selection, residual learning, and model comparison**.
- Evaluated models using **MSE, relative L2 error, one-step prediction, and recursive rollout**.
- Studied **generalization errors and error accumulation** when predictions are reused as future inputs.
- Performed **validation-based model selection and ablation studies**.
- Compared inference cost with the numerical PDE solver and measured a speedup of more than **100x** in the tested setting.
- The structured residual patterns found in this project later motivated the research paper above.

**Keywords:** supervised learning, regression, kernel methods, regularization, gradient boosting, model selection, validation, PDE surrogates

[View Repository](https://github.com/Youssef-obr/pde-surrogate-learning)

---

### No-Show Prediction Model (Healthcare Startup Prototype)

- Built a **no-show prediction model** for a women’s healthcare startup.
- Integrated the model into a **conversational prototype**:
  - A conversational assistant asks natural-language questions.
  - Relevant answers are mapped to model features.
  - The system outputs a **no-show probability** and a decision based on a configurable threshold.
- Added optional explanations of likely contributing factors.

**Keywords:** machine learning, classification, decision thresholds

---

### 3D Reconstruction from Images — Photogrammetry

Developed a Python photogrammetry pipeline to reconstruct 3D point clouds from multiple images.

- Implemented a relative-orientation approach using SIFT matching, RANSAC filtering, camera pose estimation, and triangulation.
- Reconstructed several real scenes, including a pyramid, stairs, and a topographic map.
- Evaluated the pyramid reconstruction after scale alignment, with an average relative error of about **2.47%**.
- Validated the geometric pipeline with absolute orientation for precise measurement.
- Tested LoFTR to improve matching on difficult image pairs.

**Keywords:** photogrammetry, 3D reconstruction, SIFT, RANSAC, LoFTR, triangulation, computer vision

[View Repository](https://github.com/Youssef-obr/3d-reconstruction-photogrammetry.git)

---

### Thermal Simulation & CPU Geometry Optimization (TIPE)

- Developed a **thermal simulator for CPUs** based on physical heat-transfer models.
- Implemented **geometric optimization of heat-dissipation blocks**.
- Evaluated design choices through numerical simulations.
- Studied how geometry can improve thermal dissipation and potentially increase CPU lifetime.

**Keywords:** thermal modeling, numerical simulation, optimization, physics-based modeling

[View Repository](https://github.com/Youssef-obr/CPU-Thermal-Simulation.git)

---

📫 **Contact:** youssef.oubari@imt-atlantique.net
