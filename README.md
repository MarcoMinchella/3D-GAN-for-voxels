# 3D Voxel GAN — ModelNet10

A Generative Adversarial Network for synthesizing voxelized 3D objects, trained on the **ModelNet10** dataset. The project extends GAN methodology beyond 2D image generation to produce structured volumetric data.

---

## Overview

This repository implements a 3D voxel-based GAN architecture, trained and evaluated on ModelNet10. It supports the generation of novel 3D object samples across all ten categories and provides a modular codebase covering data preprocessing, training, and visualization.

**Key features**

- 3D voxel-based GAN architecture
- Trained and evaluated on the ModelNet10 dataset
- Generation of novel 3D object samples across 10 categories
- Tools for data preprocessing, training, and visualization
- Modular code structure

---

## Dataset

[ModelNet10](https://modelnet.cs.princeton.edu/) is a subset of the ModelNet dataset containing ten object classes, including *chair*, *table*, *bed*, and *sofa*. Objects are represented as 3D voxel grids derived from the original CAD files. Preprocessing scripts for converting and preparing the data are included in the dedicated data preparation directory.

---

## Repository Structure

```
.
├── data_preparation/   # Scripts for voxelization and dataset preprocessing
├── models/             # GAN architecture (generator and discriminator)
├── training/           # Training loop and configuration
├── visualization/      # Rendering and visualization utilities
├── results/            # Generated samples (images and GIFs)
└── presentation/       # Project presentation (PowerPoint)
```

---

## Results

The trained GAN produces voxelized 3D shapes that visibly resemble the target ModelNet10 categories. Example outputs, including rendered images and animated visualizations, are provided in the `results/` directory. A full presentation of the project, covering methodology and outcomes, is available in the `presentation/` directory.

---

## Presentation

A complete walkthrough of the project — including motivation, architecture, training details, and results — is available in the accompanying PowerPoint file located in the `presentation/` directory