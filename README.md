<h1 align="center">Hi, I'm Eric</h1>

<p align="center">
  PhD student at Carnegie Mellon University building fast, reliable computational methods for scientific and engineering simulation.
  <br />
  My work spans isogeometric analysis (IGA), finite element methods, scientific machine learning, AI for Science, and biomedical simulation.
  <br />
  I am a member of the <a href="https://www.meche.engineering.cmu.edu/faculty/zhang-computational-bio-modeling-lab.html">Computational Bio-Modeling Lab</a>, advised by Prof. Yongjie Jessica Zhang.
</p>

---

## About Me

I am a PhD student at Carnegie Mellon University working at the intersection of scientific computing, physics-based simulation, and machine learning. I develop computational methods and research software that make simulation pipelines faster, more reliable, and easier to use for real scientific and engineering problems.

My current interests include:

- Isogeometric analysis, finite element methods, and high-performance PDE solvers
- Scientific machine learning and surrogate modeling
- GPU acceleration and distributed-memory parallel computing
- Biomedical transport, cardiovascular flow, and complex branching geometries
- Agentic workflows for simulation setup, execution, analysis, and iteration

## Featured Projects

### [TubularFlowIGA](https://github.com/EngineerEricXie/TubularFlowIGA)

A C++ isogeometric-analysis pipeline for stabilized steady Navier–Stokes flow and transient two-field transport in tubular and branching geometries. It includes dependency-free control-mesh generation, Bézier extraction, an MPI/PETSc CPU backend, and a single-GPU CUDA backend.

On a corrected 35,949-node neuron case, one NVIDIA V100 completed the coupled Navier–Stokes and 300-step transport computation in **279.40 s**, compared with **563.68 s** on 16 CPU ranks—a measured **2.02× speedup**. On a 4,221-node cylinder, the optimized CPU implementation's first nonlinear update was about **16.6× faster** and used **77.5% less memory** than the legacy solver; this second comparison is historical first-update evidence, not a complete converged solver-to-solver baseline.

[Repository](https://github.com/EngineerEricXie/TubularFlowIGA) · [Benchmark details](https://github.com/EngineerEricXie/TubularFlowIGA/blob/main/docs/BENCHMARKS.md)

### [NeuronTransportIGA](https://github.com/EngineerEricXie/NeuronTransportIGA)

An isogeometric-analysis workflow for material transport simulation in complex neuron geometries. The pipeline covers neuron-skeleton smoothing, hexahedral control-mesh generation, truncated hierarchical tricubic splines, Bézier extraction, METIS partitioning, and MPI-parallel Navier–Stokes and transport solvers.

[Repository](https://github.com/EngineerEricXie/NeuronTransportIGA)

### [NeuronTransportGALDS](https://github.com/CMU-CBML/NeuronTransportGALDS)

Official implementation of GALDS, a graph-autoencoder-based latent dynamics surrogate model for predicting neurite material transport.

[Repository](https://github.com/CMU-CBML/NeuronTransportGALDS) · [arXiv](https://arxiv.org/abs/2507.10871)

## Current Research

### High-Performance IGA and Simulation

Developing CPU- and GPU-accelerated IGA workflows for flow and transport in tubular, branching, and neuron geometries, with an emphasis on numerical validation, scalable preprocessing, and reproducible performance evidence.

### Scientific Machine Learning

Exploring learning-enhanced simulation methods that combine physical structure, numerical models, graph representations, and data-driven dynamics.

### Agents for Simulation Pipelines

Building agent-based tools to help automate simulation setup, execution, validation, analysis, and iteration.

## Selected Publications

- **Predicting Macroscopic Axon Topology from Microscopic Kinematics: An Interactive Tracking and Random Walk Pipeline for Substrate-Dependent Cortical Neurospheres**  
  Chunghwan Kim, Myungbo Kim, Hanlin Cao, **Tsung Yeh Hsieh**, Yongjie Jessica Zhang, Tzahi Cohen-Karni, Victoria Webster-Wood. *bioRxiv*, 2026.  
  [bioRxiv](https://www.biorxiv.org/content/10.64898/2026.07.30.741748v1) · [DOI](https://doi.org/10.64898/2026.07.30.741748)

- **GALDS: A Graph-Autoencoder-based Latent Dynamics Surrogate model to predict neurite material transport**  
  Tsung Yeh Hsieh, Yongjie Jessica Zhang.  
  [Code](https://github.com/CMU-CBML/NeuronTransportGALDS) · [arXiv](https://arxiv.org/abs/2507.10871) · [Google Scholar](https://scholar.google.com.tw/citations?user=Wu0GDnwAAAAJ&hl=zh-TW)

- **A multiscale stabilized physics informed neural networks with weakly imposed boundary conditions transfer learning method for modeling advection dominated flow**  
  Tsung Yeh Hsieh, Tsung-Hui Huang. *Engineering with Computers*, 2024.  
  [DOI](https://doi.org/10.1007/s00366-024-01981-5) · [Google Scholar](https://scholar.google.com.tw/citations?user=Wu0GDnwAAAAJ&hl=zh-TW)

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/MPI-Parallel%20Computing-6C4AB6?style=flat-square" alt="MPI" />
  <img src="https://img.shields.io/badge/PETSc-Scientific%20Computing-2F80ED?style=flat-square" alt="PETSc" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/JAX-0F9D58?style=flat-square&logo=google&logoColor=white" alt="JAX" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
</p>

## Contact

I am always open to thoughtful conversations and collaborations around scientific computing, IGA, scientific machine learning, and computational engineering.

<p>
  <a href="mailto:tsungyeh@andrew.cmu.edu">
    <img src="https://img.shields.io/badge/Email-tsungyeh%40andrew.cmu.edu-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/EngineerEricXie">
    <img src="https://img.shields.io/badge/GitHub-EngineerEricXie-181717?style=flat-square&logo=github" alt="GitHub" />
  </a>
  <a href="https://scholar.google.com.tw/citations?user=Wu0GDnwAAAAJ&hl=zh-TW">
    <img src="https://img.shields.io/badge/Google%20Scholar-Profile-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar" />
  </a>
  <a href="https://www.meche.engineering.cmu.edu/faculty/zhang-computational-bio-modeling-lab.html">
    <img src="https://img.shields.io/badge/Lab-CMU%20CBML-C41230?style=flat-square" alt="CMU CBML" />
  </a>
</p>

---

<p align="center">
  <i>Building accelerated, learning-enhanced simulation tools for science and engineering.</i>
</p>
