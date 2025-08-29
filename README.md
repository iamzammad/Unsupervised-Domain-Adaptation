# Unsupervised Domain Adaptation

This repository contains code and experiments for Unsupervised Domain Adaptation (UDA).

## 📌 Overview
The project explores methods to improve model robustness against **domain shifts** – when training (source) and testing (target) distributions differ. Two main paradigms are studied:

- **Unsupervised Domain Adaptation (UDA):** Leveraging labeled source data and unlabeled target data to align feature spaces for better transfer performance.  
- **Domain Generalization (DG):** Training on multiple source domains to learn invariant features that generalize well to unseen target domains.  

Key tasks include:
- Implementing and evaluating **ResNet, DAN (Domain Adaptation Network), and DANN (Domain-Adversarial Neural Network)** for UDA on datasets like **Office-31, Office-Home, and Digits**.  
- Applying **Invariant Risk Minimization (IRM) variants** (IRM Basic, IB-IRM, PAIR) for DG on datasets such as **Rotated MNIST, PACS, and VLCS**.  
- Exploring **Disentangled Representation Learning (β-VAE)** to separate generative factors and study interpretability across datasets like **CelebA, 3D Chairs, and dSprites**.  

The repo demonstrates how **adaptation, invariance, and disentanglement methods** improve out-of-distribution generalization, comparing their strengths, limitations, and trade-offs.
