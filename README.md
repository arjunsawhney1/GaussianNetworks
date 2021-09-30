# Gaussian Radial Basis Networks
In this repo, I explore Gaussian Radial Basis Networks and their utility in classification tasks

## Data.
I generate 2-d and 4-d data using the `sklearn.datasets` package. 

## The Problem
Classification of data points is often difficult using a simple least squares classifier without any feature engineering. 
Gaussian Radial Basis Functions arise as a simple solution to transform the dimensionality of the data to a higher dimensional space where the data is linearly separable

## Methodology
In this notebook, I compare prediction accuracy of a least squares classifier before and after feature transformation.
I also discuss how to use K-means to choose better RBF locations for efficient classification
