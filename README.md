# 3D Voxel GAN — ModelNet10

A Generative Adversarial Network for synthesizing voxelized 3D objects, trained on the **ModelNet10** dataset. The project extends GAN methodology beyond 2D image generation to produce structured volumetric data.

-----

## Overview

This repository implements a 3D voxel-based GAN architecture, trained and evaluated on ModelNet10. It supports the generation of novel 3D object samples across all ten categories and provides a modular codebase covering data preprocessing, training, and visualization.

**Key features**

- 3D voxel-based GAN architecture
- Trained and evaluated on the ModelNet10 dataset
- Generation of novel 3D object samples across 10 categories
- Tools for data preprocessing, training, and visualization
- Modular code structure

-----

## Dataset

[ModelNet10](https://modelnet.cs.princeton.edu/) is a subset of the ModelNet dataset containing ten object classes, including *chair*, *table*, *bed*, and *sofa*. Objects are represented as 3D voxel grids derived from the original CAD files. Preprocessing scripts for converting and preparing the data are provided in the `Data preparation/` directory.

-----

## Repository Structure

```
.
├── Data preparation/                          # Voxelization and dataset preprocessing scripts
├── Datasets/                                  # ModelNet10 data
├── PPT images and gifs/                       # Generated samples and visualizations
├── 3D_GAN_project.ipynb                       # Main notebook (training and evaluation)
├── 3d_gan_project.py                          # Script version of the project
├── 3D VISION & EXTENTED REALITY PROJECT.pptm  # Project presentation
└── README.md.                                 # You're reading it
```

-----

## Results

The trained GAN produces voxelized 3D shapes that visibly resemble the target ModelNet10 categories. Example outputs, including rendered images and animated visualizations, are available in the `PPT images and gifs/` directory.

-----

## Presentation

A complete walkthrough of the project — covering motivation, architecture, training details, and results — is provided in `3D VISION & EXTENTED REALITY PROJECT.pptm`.