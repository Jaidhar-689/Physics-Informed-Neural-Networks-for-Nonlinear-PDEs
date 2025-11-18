# Physics-Informed Neural Networks for Nonlinear PDEs

*Ongoing Project — Full Code Release on **1st December***

This repository hosts an ongoing project exploring the use of **Physics-Informed Neural Networks (PINNs)** to solve **nonlinear Partial Differential Equations (PDEs)**. The goal is to build reliable neural solvers for challenging physical systems where traditional numerical methods struggle, especially near shocks, discontinuities, and stiff regimes.

The first version of the code—including training scripts, model architectures, baselines, and experiment results—will be uploaded by **1st December**.
---

## 🔬 Project Overview

This project explores the use of **Physics-Informed Neural Networks (PINNs)** to solve nonlinear and high-dimensional physical systems. The current focus is on three PDE models:

* **Burgers’ Equation** — used as a baseline to validate the PINN framework
* **Riemann Problem** — solving for density and velocity evolution with shock formation
* **Kinematic Dynamo Equation** — modeling magnetic field evolution in conducting fluids

The implementation includes:

* Formulating the governing PDEs, initial conditions, and boundary conditions directly into the loss function
* Using automatic differentiation to compute exact PDE residuals
* Training PINNs to recover smooth as well as discontinuous dynamics
* Comparing model predictions with analytical or numerical reference solutions
---

## 📅 Expected Release

The full project (source code, plots, trained models, and documentation) will be published by:

**📌 Release Date: 1st December**
