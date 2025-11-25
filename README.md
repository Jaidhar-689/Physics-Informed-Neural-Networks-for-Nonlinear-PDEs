# Physics-Informed Neural Networks for Nonlinear PDEs

This repository contains implementations of **Physics-Informed Neural Networks (PINNs)** for solving several nonlinear and high-dimensional PDEs. The project includes experiments on smooth, discontinuous, and vector-valued systems, along with saved models and a full project report.

---

## 📂 Repository Structure

* **`PINN_code/PINN_s/`** — All PINN training scripts, model definitions, and experiment code
* **`NN_Models/NN_Models/`** — Saved neural-network models with short notes on each run
* **`Btech_Project_Report.pdf`** — Full project report summarizing methods, results, and analysis 

---

## 🔬 PDEs Implemented

The project explores PINNs on multiple systems of increasing difficulty:

* **Burgers’ Equation** — baseline test for nonlinear advection–diffusion
* **Riemann Problem** — studying shock formation and activation-function effects
* **3D Heat Equation** — scaling PINNs to four input dimensions
* **Kinematic Dynamo (2D & 3D)** — testing PINN limits on vector-valued, curl-driven PDEs

Each model encodes the governing PDE, initial conditions, and boundary conditions directly into a composite loss function using automatic differentiation (PyTorch).

---

## 🧠 Key Features

* Fully connected PINN architectures in PyTorch
* PDE residuals computed via automatic differentiation
* Adam + L-BFGS training pipeline
* Experiments comparing different activations, sampling strategies, and loss weights
* Saved models for reproducibility and further exploration

---

## 📘 Report

The full project report (methods, equations, figures, and detailed analysis) is included as:

**`Btech_Project_Report.pdf`** 

---

## 📌 Status

All code, results, and models are now uploaded. Future updates may include improved architectures (FNOs, spectral PINNs) and extended kinematic dynamo experiments.
