# TWIM: Temporal Influence Maximization Framework

This repository will host the official implementation of the **TWIM** framework for Temporal Influence Maximization in social networks using a modified Grey Wolf Optimizer (GWO).

## 📢 Current Status: Under Review (Revision Stage)
The source code is currently kept **private** as the corresponding manuscript is undergoing the final peer-review process. 

**The full implementation, datasets, and execution guides will be made fully Open-Source immediately upon the official publication of the paper.**

---

## 🚀 Framework Overview
* **Temporal Diffusion Modeling:** Simulates information spread using a discrete-time Temporal Independent Cascade (T-IC) model, integrating continuous-time exponential decay ($\lambda$).
* **Scenario-Based Optimization:** Supports time-critical network scenarios, specifically focusing on the high-performance **TWIM-S2** configuration.
* **Vibrancy Fitness Surrogate:** Employs an activity-logarithmic proxy to efficiently balance interaction frequency and temporal recency.
* **Extensive Benchmarking:** Includes comparative baselines such as T-CELF, MATI, T-Degree, T-PageRank, and Static GWO.

## 📊 Datasets
The framework's structural resilience and adaptability are evaluated across diverse temporal topologies:
* **Cit-HepPh** (Academic citation network)
* **CollegeMsg** (High-velocity online messaging)
* **Email-Eu & Dept2** (Institutional communication networks)

## 📈 Statistical Validation
All performance trajectories and comparative claims reported in the manuscript are rigorously validated over 30 independent stochastic trials using non-parametric **Wilcoxon signed-rank tests** ($p < 0.01$).

## 📖 Proposed Citation
If you wish to track this project, please note that it is related to the following upcoming publication:

> *Tabatabaei, A., et al. "TWIM: Temporal Influence Maximization in Social Networks with Grey Wolf Optimization", Computing (Springer Nature), 2026 (Under Revision).*
