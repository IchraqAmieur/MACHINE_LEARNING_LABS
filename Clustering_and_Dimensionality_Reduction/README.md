# LAB5: Clustering and Dimensionality Reduction on Image Data

## Overview
This lab explores unsupervised learning techniques—clustering and dimensionality reduction—using a subset of the CIFAR-10 image dataset. The workflow demonstrates how to preprocess, visualize, cluster, and evaluate high-dimensional image data.

### 1. Dataset Preparation
- Imported the CIFAR-10 dataset and selected four classes: airplane, automobile, bird, and cat.
- Visualized sample images with their labels to understand the data distribution.
- Normalized image pixel values to the [0, 1] range.

### 2. Dimensionality Reduction
- Applied Principal Component Analysis (PCA) to reduce data to two components for visualization and to 95% variance for clustering.
- Used Linear Discriminant Analysis (LDA) to reduce data to three components for enhanced class separability.
- Visualized the data in 2D after dimensionality reduction.

### 3. Clustering
- Performed K-means clustering on the normalized data, on PCA-reduced data, and on LDA-reduced data.
- Visualized clustering results in 2D for each approach and compared cluster separation.

### 4. Evaluation
- Computed Davies-Bouldin scores to assess cluster quality for all models.
- Displayed confusion matrices and classification reports to evaluate clustering performance.
- Showcased misclassified images for the best model, highlighting true and predicted labels.

### 5. Model Improvement
- Explored strategies to enhance the performance of the best clustering model.

## Key Takeaways
- Developed practical skills in dimensionality reduction (PCA, LDA) and clustering (K-means) for image data.
- Learned to visualize and interpret high-dimensional data and clustering results.
- Gained experience in evaluating unsupervised models using quantitative and qualitative metrics.

## Why This Matters
Clustering and dimensionality reduction are essential for understanding and organizing complex datasets like images. This lab demonstrates my ability to apply, evaluate, and improve unsupervised learning techniques in real-world scenarios.