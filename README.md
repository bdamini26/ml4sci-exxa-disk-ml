# ML4SCI EXXA Disk Machine Learning

This repository contains my submission for the EXXA project tests for the ML4SCI GSoC program.

The project explores machine learning approaches to analyze synthetic ALMA observations of protoplanetary disks.

## Tests Implemented

### 1. General Test
Notebook: `disk_clustering.ipynb`

- Loads FITS disk images
- Preprocesses telescope observations
- Applies PCA dimensionality reduction
- Performs KMeans clustering
- Visualizes clusters of disk morphologies

### 2. Image Test
Notebook: `exxa_autoencoder.ipynb`

- Implements an autoencoder model
- Learns latent representations of disk images
- Reconstructs protoplanetary disk structures

## Tools Used
- Python
- Astropy
- Scikit-learn
- PyTorch
- Matplotlib

## Dataset
Synthetic ALMA protoplanetary disk simulations provided for the EXXA ML4SCI test.

Author:Bandi Damini
