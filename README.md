# Clustering Project

This repository contains code for clustering 2D data and MNIST dataset using K-means algorithm.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)

## Introduction

Clustering is a type of unsupervised learning algorithm that aims to partition a dataset into groups, or clusters, based on similarity. In this project, we apply the K-means clustering algorithm to two datasets:
1. A 2D dataset (`data_2d.csv`)
2. MNIST dataset (`mnist.csv`)

For the 2D dataset, we visualize the clustering result and use the elbow method to determine the optimal number of clusters. For the MNIST dataset, we also use PCA (Principal Component Analysis) to reduce the dimensionality of the data to two dimensions before clustering.

## Installation

To run the code in this repository, you need to have Python installed. You also need to install the following Python libraries:

- pandas
- numpy
- scikit-learn
- matplotlib

You can install these libraries using pip:

```bash
pip install pandas numpy scikit-learn matplotlib

##Usage

1. Clone this repository to your local machine.
2. Navigate to the directory containing the code.
3. Make sure you have the datasets data_2d.csv and mnist.csv in the same directory.
4. Run the Jupyter Notebook or Python script to perform clustering on the datasets.






