# GMM-from-Scratch
GMM on Astrolab from Scratch
# Gaussian Mixture Model (GMM) on Astrolab Data

## Overview
This project implements a **Gaussian Mixture Model (GMM)** from scratch using **NumPy** to cluster astronomical data from the Sloan Digital Sky Survey (SDSS). GMM is a probabilistic clustering algorithm that models data as a mixture of multiple Gaussian distributions, making it particularly useful for unsupervised learning tasks like grouping stars or galaxies based on spectral features.

In addition to building the GMM manually, I compared the results with scikit-learn's implementation to validate accuracy and explore performance differences.

---

## Features
- **Custom Implementation:** GMM built from scratch using NumPy, including the E-step, M-step, and convergence checks.
- **Covariance Calculations:** Manual computation of covariance matrices for multivariate Gaussians.
- **Mahalanobis Distance:** Used for more accurate clustering with non-spherical Gaussian components.
- **Comparison with scikit-learn:** Benchmarked against scikit-learn's `GaussianMixture` implementation to validate results.
- **Astronomical Data:** Used spectral data from the **Sloan Digital Sky Survey (SDSS)** for a real-world application.
