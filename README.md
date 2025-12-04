Customer Segmentation using KMeans, PCA, and Silhouette Analysis
Project Overview

This project performs customer segmentation using KMeans clustering based on three numerical features:

Age

Salary

Spending Score

To visualize the clusters effectively, PCA (Principal Component Analysis) is applied to reduce the dataset from 3D to 2D.

The project also evaluates clustering quality using Silhouette Score and displays multiple visualizations, including:

PCA Cluster Plot

Age vs Salary Cluster Plot

Silhouette Value Bar Chart

Objectives

Build a customer dataset

Apply KMeans clustering

Use PCA for dimensionality reduction

Visualize clusters in 2D

Calculate Silhouette Score to evaluate cluster quality

Perform descriptive analysis of each cluster

Technologies Used

Python

Pandas

Scikit-learn

Matplotlib

Numpy

Installation

Install Python (recommended 3.8 or higher).

Install required libraries:

pip install pandas scikit-learn matplotlib numpy

How to Run the Project

Copy the full script into a file named:

customer_segmentation.py


Run the file:

python customer_segmentation.py


The program will output:

Dataset

Cluster labels

PCA components

Silhouette score

Cluster-wise descriptive statistics

Visualizations

Project Workflow
1. Dataset Creation

A dataset of 10 customers is created containing Age, Salary, and Spending Score.

2. KMeans Clustering

KMeans (with 2 clusters) is applied on the features:

['Age', 'Salary', 'SpendingScore']

3. PCA Transformation

PCA reduces the original 3 features into 2 components for visualization.

4. Silhouette Score

Silhouette Score evaluates cluster separation and cohesion.

5. Visualization

The project includes:

PCA scatter plot

Age vs Salary cluster scatter plot

Silhouette value bar chart

6. Cluster Interpretation

Each cluster is analyzed using descriptive statistics:

Age distribution

Salary distribution

Spending Score distribution

Example Insights

Based on your project output:

Cluster 0:

Younger customers

Lower to mid salary levels

High spending score

Cluster 1:

Older customers

High salary levels

Low spending score

This helps companies identify:

High-value spenders

Potential premium customers

Customers with low spending despite high salary

Complete Code Used in This Project

Your full script (as executed) includes:

Dataset creation

KMeans clustering

PCA transformation

Silhouette analysis

Multiple visualizations

Cluster summary statistics
