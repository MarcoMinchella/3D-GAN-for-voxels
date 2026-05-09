A Generative Adversarial Network for synthesizing voxelized 3D objects, trained on the ModelNet10 dataset. The project extends GAN methodology beyond 2D image generation to produce structured volumetric data.
Overview
The repository implements a 3D voxel-based GAN architecture, trained and evaluated on ModelNet10. It supports generation of novel 3D object samples across all ten categories and provides a modular codebase covering data preprocessing, training, and visualization.
Dataset
ModelNet10 is a subset of the ModelNet dataset containing ten object classes, including chair, table, bed, and sofa. Objects are represented as 3D voxel grids derived from the original CAD files. Preprocessing scripts for converting and preparing the data are included in the dedicated data preparation directory.
Results
The trained GAN produces voxelized 3D shapes that visibly resemble the target ModelNet10 categories. Example outputs, including rendered images and animated visualizations, are provided in the dedicated results directory. A full presentation of the project, covering methodology and outcomes, is available in the accompanying PowerPoint file.