# Unsupervised Forest Cover Type Prediction

This repository contains the code and analysis for predicting forest cover types using unsupervised clustering techniques. The project explores the effectiveness of clustering algorithms compared to traditional classification methods on the UCI Cover Type dataset.

## Project Overview

- **Objective**: Evaluate the performance of unsupervised clustering techniques for predicting forest cover types.
- **Dataset**: UCI Cover Type dataset with 54 features and 7 forest cover types.
- **Approach**: 
  - Data exploration and preprocessing, including dimensionality reduction using PCA.
  - Comparison of clustering algorithms (KMeans, Affinity Propagation, Mean Shift, Birch) with baseline classifiers (SVC, KNN, Decision Tree).
  - Custom clustering accuracy metric to compare cluster assignments with ground-truth labels.

## Key Findings

- **Clustering Performance**: Affinity Propagation and Mean Shift achieved high accuracy scores but were prone to overfitting due to creating too many clusters.
- **Dimensionality Reduction**: PCA improved clustering performance, with 7 principal components yielding the best results for KMeans.
- **Baseline Comparison**: Clustering algorithms (KMeans, Birch) did not surpass the performance of baseline classifiers, suggesting that traditional classification methods are more suitable for this task.

## Requirements

- Python 3.10
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn

## Contributors

- Franciszek Latała
- Henry Page
- David Sulu
