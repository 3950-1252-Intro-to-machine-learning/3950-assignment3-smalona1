[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/hEGQjSR-)
# Assignment: Generative Modeling with Gaussian Mixture Models (GMM)

## Using GMM to Learn and Generate Handwritten Digit Images

### Overview

In this assignment you will use **Gaussian Mixture Models (GMM)** to learn the distribution of handwritten digit images from the MNIST dataset, and then use the trained model to **generate brand new synthetic digit images**.

This demonstrates the core idea behind **generative models** — the same family of concepts that powers GANs, diffusion models, and large language models.

### Learning Objectives

- Load and explore image data (MNIST)
- Apply PCA for dimensionality reduction before clustering
- Fit a GMM to high-dimensional image data
- Sample from a trained GMM to generate new synthetic images
- Compare all-digit vs. per-digit generative models
- Understand the relationship between GMM and modern generative AI

### Files

| File | Description |
|------|-------------|
| `gmm_image_generation_assignment.ipynb` | **Student version** — scaffolded notebook with TODO placeholders |
| `requirements.txt` | Python dependencies |


   ```

> **Note:** The MNIST dataset is downloaded automatically by `sklearn.datasets.fetch_openml` on first run. An internet connection is required for the first execution.

### Grading Breakdown (100 marks)

| Part | Topic | Marks |
|------|-------|-------|
| 1 | Data Loading & Exploration | 10 |
| 2 | PCA Dimensionality Reduction | 15 |
| 3 | Fit GMM to All Digits | 20 |
| 4 | Generate New Digit Images | 20 |
| 5 | Per-Digit GMM Generation | 25 |
| 6 | Reflection Questions | 10 |




