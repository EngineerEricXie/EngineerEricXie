<h1 align="center">Hi, I'm Eric</h1>

<p align="center">
  PhD student at Carnegie Mellon University building machine-learning systems for scientific and engineering problems.
  <br />
  My work spans graph neural networks, Neural ODEs, scientific machine learning, AI agents, and GPU-accelerated simulation.
  <br />
  I am a member of the <a href="https://www.meche.engineering.cmu.edu/faculty/zhang-computational-bio-modeling-lab.html">Computational Bio-Modeling Lab</a>, advised by Prof. Yongjie Jessica Zhang.
</p>

---

## About Me

I develop AI methods that learn physical dynamics, accelerate simulation, and automate scientific workflows. My research combines machine learning with numerical modeling for biomedical and engineering applications.

- Graph neural networks, Neural ODEs, transformers, PINNs, and surrogate models
- AI agents for simulation and research automation
- GPU-accelerated scientific computing and high-performance PDE solvers
- Biomedical transport, neural systems, and complex geometries

## Featured Projects

### [NeuronTransportGALDS](https://github.com/CMU-CBML/NeuronTransportGALDS)

A graph-autoencoder and Neural ODE surrogate model for predicting material transport in complex neurite networks.

**Results:** approximately **3% mean relative error**, **<8% maximum relative error**, **10× faster inference**, **20× less training data**, **10× fewer trainable parameters**, and **6× faster training** than the prior surrogate approach.

[Repository](https://github.com/CMU-CBML/NeuronTransportGALDS) · [Paper](https://doi.org/10.1016/j.cma.2025.118409)

### [TubularFlowIGA](https://github.com/EngineerEricXie/TubularFlowIGA)

A C++ CPU/GPU isogeometric-analysis pipeline for flow and transport in tubular and branching geometries.

**Results:** compared with the [legacy NeuronTransportIGA baseline](https://github.com/EngineerEricXie/NeuronTransportIGA), the optimized CPU path achieved **up to 16.6× faster computation** and **77.5% less memory use**; the CUDA backend delivered a **2.02× speedup over the optimized CPU solver**.

[Repository](https://github.com/EngineerEricXie/TubularFlowIGA) · [Benchmarks](https://github.com/EngineerEricXie/TubularFlowIGA/blob/main/docs/BENCHMARKS.md)

### [NeuronTransportIGA](https://github.com/EngineerEricXie/NeuronTransportIGA)

An end-to-end parallel IGA platform for simulating flow and material transport in complex neuron geometries.

[Repository](https://github.com/EngineerEricXie/NeuronTransportIGA)

## Current Research

### Machine Learning for Physical Systems

Building graph neural networks, Neural ODEs, transformers, PINNs, and surrogate models that learn physical dynamics and generalize across geometries and conditions.

### AI Agents for Scientific Computing

Developing agents that automate simulation setup, execution, validation, analysis, and iterative scientific workflows.

### Scalable Scientific Computing

Creating GPU-accelerated and parallel simulation tools that generate training data, provide physical priors, and support reliable AI-for-science systems.

## Selected Publications

- **Predicting Macroscopic Axon Topology from Microscopic Kinematics: An Interactive Tracking and Random Walk Pipeline for Substrate-Dependent Cortical Neurospheres**  
  Chunghwan Kim, Myungbo Kim, Hanlin Cao, **Tsung Yeh Hsieh**, Yongjie Jessica Zhang, Tzahi Cohen-Karni, Victoria Webster-Wood. *bioRxiv*, 2026.  
  [bioRxiv](https://www.biorxiv.org/content/10.64898/2026.07.30.741748v1) · [DOI](https://doi.org/10.64898/2026.07.30.741748)

- **GALDS: A Graph-Autoencoder-based Latent Dynamics Surrogate model to predict neurite material transport**  
  Tsung Yeh Hsieh, Yongjie Jessica Zhang. *Computer Methods in Applied Mechanics and Engineering*, 2025.  
  [Code](https://github.com/CMU-CBML/NeuronTransportGALDS) · [Paper](https://doi.org/10.1016/j.cma.2025.118409) · [Google Scholar](https://scholar.google.com.tw/citations?user=Wu0GDnwAAAAJ&hl=zh-TW)

- **A multiscale stabilized physics informed neural networks with weakly imposed boundary conditions transfer learning method for modeling advection dominated flow**  
  Tsung Yeh Hsieh, Tsung-Hui Huang. *Engineering with Computers*, 2024.  
  [Paper](https://doi.org/10.1007/s00366-024-01981-5) · [Google Scholar](https://scholar.google.com.tw/citations?user=Wu0GDnwAAAAJ&hl=zh-TW)

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/JAX-0F9D58?style=flat-square&logo=google&logoColor=white" alt="JAX" />
  <img src="https://img.shields.io/badge/Graph%20Neural%20Networks-6C4AB6?style=flat-square" alt="Graph Neural Networks" />
  <img src="https://img.shields.io/badge/Neural%20ODEs-2F80ED?style=flat-square" alt="Neural ODEs" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/MPI%20%7C%20PETSc-Scientific%20Computing-555555?style=flat-square" alt="MPI and PETSc" />
</p>

## Contact

I am open to conversations and collaborations around scientific machine learning, AI for physical systems, AI agents, and computational engineering.

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
  <i>Building AI systems that learn, accelerate, and automate physical simulation.</i>
</p>
