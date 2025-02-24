# AI-Master's-Thesis

Enhancing Spiking Neural Networks for FMNIST Classification Optimisation Techniques and Finetuning Strategies

📌 Overview
This repository contains the research and implementation of Spiking Neural Networks (SNNs) for classifying the Fashion MNIST (FMNIST) dataset. The study explores various optimisation techniques and fine-tuning strategies to enhance the performance of SNNs, comparing their effectiveness against traditional ANN models.

📄 Thesis Details
Author: Aditya
Degree: MSc Artificial Intelligence and Adaptive Systems
University: University of Sussex
Supervisor: Dr. Thomas Nowotny
Year: Summer 2024
Word Count: 12,000

🎯 Objectives
Investigate optimisation techniques to enhance SNN performance.
Develop fine-tuning strategies to improve robustness and accuracy.
Compare optimised SNNs with traditional ANN & SNN-based approaches.
🛠️ Methodology
Dataset: Fashion MNIST (FMNIST)

Frameworks: torch, torchvision, pytorch-spiking, matplotlib, numpy

Model Architecture:
Convolutional Layers: Extract spatial features
LIF (Leaky Integrate-and-Fire) Neurons: Introduce spiking behavior
Fully Connected Layers: Classify images into 10 categories

Optimisation Strategies:
Dropout Regularisation
Batch Normalisation
Learning Rate Annealing
Gradient Descent Optimisation
Adam Optimiser with Learning Rate Scheduler

🔬 Results
Baseline Accuracy: 86.01%
Best Optimisation Strategy: Learning Rate Annealing (Cosine Annealing) – 88.36%
Final Test Accuracy (on unseen data): 87.82%

📌 Key Findings
Learning Rate Annealing significantly improves SNN classification accuracy.
Traditional techniques like dropout and batch normalisation are moderately effective for SNNs.
Future research should explore hybrid fine-tuning methods and neuromorphic hardware implementations.


