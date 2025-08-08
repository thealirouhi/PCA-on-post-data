# Principal Component Analysis (PCA) on Handwritten Digits
This project is a report demonstrating the implementation of the Principal Component Analysis (PCA) algorithm on a dataset of handwritten digits. The goal was to reduce the data's dimensionality from 64D (for each 8x8 pixel image) to 2D and visualize the results to observe how different digits form distinct clusters.

The complete analysis and step-by-step process are presented in the project.html file.

## Project Overview
This analysis was conducted for a linear algebra course and walks through the essential steps of the PCA algorithm. The dataset consists of handwritten digits from a postal service, where each digit is represented as a vector of pixel values.

The key steps detailed in the report are:

Data Loading and Preparation: The digits.csv dataset is loaded and prepared for analysis.

Data Scaling: Pixel values are scaled to have a mean of 0 and a standard deviation of 1, preventing features with large value ranges from dominating the analysis.

Covariance Matrix Calculation: The covariance matrix of the scaled data is computed.

Eigenvalue and Eigenvector Computation: The eigenvalues and eigenvectors of the covariance matrix are calculated. These eigenvectors (Principal Components) represent the directions of maximum variance in the data.

Dimensionality Reduction: The data is projected onto the first two principal components, reducing its dimensionality to 2D.

Visualization & Analysis: The 2D data is plotted to visualize the clusters of the handwritten digits, followed by an analysis of the results.

## Key Findings 📊
The final 2D plot reveals that some digits form distinct, easily separable clusters, while others overlap significantly.

Digits 0 and 6 are clearly distinguishable from the other numbers, forming tight, isolated clusters.

Other digits show more overlap, suggesting they are harder to differentiate from one another based purely on their pixel data.

This analysis helps the postal company understand which digits might be more challenging for an automated recognition system, guiding them on where to focus data collection efforts.

## How to View the Project
There is nothing to install or run. Simply open the project.html file in a web browser to view the full report and analysis.

## Tools Used for the Analysis
The analysis presented in the report was performed using the following tools:

Python

NumPy: For numerical operations, especially linear algebra functions.

Pandas: For data manipulation and loading the CSV file.

Matplotlib & Seaborn: For data visualization.
