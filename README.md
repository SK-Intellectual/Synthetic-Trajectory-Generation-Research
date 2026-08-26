# Synthetic Trajectory Generation Through Convolutional Neural Networks

## Research Project

This repository documents my research work on **synthetic trajectory generation using convolutional neural networks (CNNs)**, conducted during my research internship at the **University of New South Wales (UNSW)** under the supervision of **Dr. Erik Buchholz**, with research in the broader trajectory-privacy work led by **Prof. Salil S. Kanhere**.

The work is based on the **CNN-TrajGAN / CNN-based trajectory generation** research developed by Jesse Merhi, Erik Buchholz, and Salil S. Kanhere. Their research investigates whether convolutional architectures, which have been highly successful in generative modeling for other domains, can be adapted for the generation of realistic synthetic mobility trajectories.

---

## Overview

Location trajectory data is valuable for applications such as urban planning, transportation analysis, and location-based services. However, mobility traces can also reveal sensitive information about individuals.

Synthetic trajectory generation provides a potential approach to releasing useful mobility data without directly publishing individuals' original trajectories. The research explores **Generative Adversarial Networks (GANs)** as a means of learning trajectory characteristics and generating synthetic trajectories that preserve useful statistical and spatial properties while reducing direct exposure of real mobility traces.

A central motivation of this research is to investigate whether **Convolutional Neural Networks (CNNs)** can provide an effective alternative to the recurrent architectures commonly used for sequential trajectory generation.

---

## My Research Contribution

During my internship, I worked on research related to **CNN-based synthetic trajectory generation**, focusing on the development and evaluation of approaches for generating variable-length mobility trajectories.

My work included:

* Investigating CNN-based architectures for synthetic trajectory generation.
* Developing preprocessing and masking strategies for handling variable-length trajectories.
* Working with PyTorch-based computational workflows for trajectory modeling.
* Investigating the robustness and behavior of CNN-based generative approaches.
* Evaluating generated trajectories against existing trajectory-generation approaches.
* Analyzing the quality and characteristics of generated trajectory data.
* Comparing the behavior of CNN-based approaches with established recurrent architectures.

The research built upon the CNN-TrajGAN direction developed by the research team and contributed to my understanding of **generative modeling, trajectory privacy, deep learning, and spatial-temporal data generation**.

---

## Research Context

The broader research question can be summarized as:

> **Can convolutional neural networks be effectively used to generate realistic synthetic mobility trajectories while providing useful privacy and utility properties?**

Traditional trajectory-generation approaches have frequently relied on recurrent neural networks because trajectories naturally have a sequential structure. CNN-based generative architectures provide an alternative perspective, drawing from the success of convolutional architectures in other generative modeling applications.

The research therefore examines the trade-offs between:

* **Trajectory realism**
* **Spatial and temporal characteristics**
* **Model robustness**
* **Privacy considerations**
* **Computational efficiency**
* **Architecture choice**

---

## Results & Visualizations

This repository contains selected visualizations and outputs from the research.

The figures are provided to demonstrate aspects of:

* Generated trajectory distributions
* Spatial characteristics of synthetic trajectories
* Model behavior
* Comparative results
* Research findings

> **Note:** The visualizations included here are intended to document the research and its outcomes rather than provide a complete reproduction package.

---

## Code Availability

The implementation and source code associated with this internship research are **not included in this repository**.

The underlying codebase and research implementation were developed within a confidential research environment at UNSW and are therefore not publicly released here.

This repository is consequently intended as a **research showcase and documentation of the work**, rather than a software distribution or reproducibility package.

---

## Research Background

This work is related to the published research:

**Jesse Merhi, Erik Buchholz, and Salil S. Kanhere.**
*Synthetic Trajectory Generation Through Convolutional Neural Networks.*

The research investigates CNN-based approaches for synthetic trajectory generation and considers their potential application to privacy-preserving trajectory publication.

The broader research group has also investigated the privacy and utility characteristics of trajectory-generation approaches, including comparisons across multiple sequential generative models.

---

## Acknowledgements

I would like to acknowledge **Dr. Erik Buchholz** for his supervision and guidance during my research internship at UNSW, and **Prof. Salil S. Kanhere** for his broader supervision and research leadership in the area of trajectory privacy and synthetic trajectory generation.

I am grateful for the opportunity to contribute to research at the intersection of **deep learning, privacy-preserving data generation, and mobility analytics**.

---

## Disclaimer

This repository presents selected research material, methodology, and outputs from my internship project. It does **not** contain the confidential source code, internal datasets, or proprietary research infrastructure used during the project.

The repository is intended for **research documentation and portfolio purposes**.

---

## Keywords

`Synthetic Trajectory Generation` · `CNN` · `GAN` · `CNN-TrajGAN` · `Trajectory Privacy` · `Mobility Data` · `Deep Learning` · `Generative Models` · `PyTorch` · `Privacy-Preserving Machine Learning`
