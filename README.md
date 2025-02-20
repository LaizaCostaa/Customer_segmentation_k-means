## Customer Segmentation with K-Means Clustering

This repository contains a Python-based implementation of the K-Means clustering algorithm, designed for customer segmentation. The project was developed as part of a Data Mining course (Mineração de Dados) and leverages scikit-learn for clustering and matplotlib for data visualization.

## Overview

Overview
Customer segmentation is essential for targeted marketing and improved customer relationship management. This project applies the K-Means algorithm to group customers based on purchasing behavior and other relevant attributes, allowing for more focused business strategies.

## Features

- **Customer Segmentation: Group customers based on their purchasing behavior and demographic features.
- **K-Means Algorithm: Utilizes scikit-learn's KMeans class to perform clustering.
- **Data Visualization: Provides basic visualizations using matplotlib to help interpret and analyze clustering results.

## Technical Details

The code implements the K-Means algorithm using the `sklearn.cluster.KMeans` class. The algorithm works by iteratively assigning data points to clusters based on their proximity to the cluster centroids. The code defines a function `calculate_cluster_centers` to determine the centroids of each cluster.

The code also includes a function `plot_clusters` to visualize the clusters. This function uses matplotlib to plot the data points and their assigned cluster labels.

## Usage

Open the Jupyter Notebook file customer_segmentation_k_means_pynb.ipynb to interact with the code.
Modify parameters such as the number of clusters or input data as needed to tailor the segmentation to your dataset.

## Final Considerations

The code provides a basic framework for customer segmentation using K-Means. Further improvements could include:

- **Feature Engineering:** Exploring additional features and attributes to improve the accuracy of the segmentation.
- **Hyperparameter Tuning:** Optimizing the K-Means algorithm's hyperparameters for better performance.
- **Ensemble Methods:** Combining multiple K-Means models for enhanced accuracy.

## About
This project was developed for the course "Mineração de Dados" (Data Mining) and demonstrates a basic framework for performing customer segmentation using unsupervised machine learning techniques.
