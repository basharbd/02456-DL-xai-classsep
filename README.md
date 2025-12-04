# Quantitative Class Separation Metrics for Hidden Representations

This repository contains the code and results for my 02456 Deep Learning project at DTU.

## Overview

We implement three supervised class-separation metrics on hidden representations of CNNs:

- **Fisher-like scatter ratio**
- **Centroid margin ratio**
- **Supervised silhouette score**

These metrics are applied to convolutional networks trained on **MNIST** and **CIFAR-10**, and tracked across epochs to study how class separation evolves during training.



## Data

The notebooks assume a `data/` folder for MNIST and CIFAR-10, but datasets are **downloaded automatically** via `torchvision.datasets` if not present.

## Environment

Typical dependencies:

- `torch`, `torchvision`
- `numpy`
- `matplotlib`
- `scikit-learn`

You can install them with:

```bash
pip install torch torchvision numpy matplotlib scikit-learn
