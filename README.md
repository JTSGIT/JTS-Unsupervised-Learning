# Wholesale Customer Segmentation Project

## Overview
This project applies unsupervised learning techniques to segment wholesale customers based on their annual spending on various product categories. The dataset used in this project contains data on different products sold by a grocery wholesaler.

## Objectives
- To identify distinct groups or segments within the wholesale customers based on their purchasing patterns.
- To determine the optimal number of clusters for segmentation using the KMeans clustering algorithm.
- To leverage PCA for dimensionality reduction and enhance clustering performance.

## Data Description
The dataset, referred to as "Wholesale Data", includes the following features:
- **Fresh**: Annual spending on fresh products.
- **Milk**: Annual spending on milk products.
- **Grocery**: Annual spending on grocery products.
- **Frozen**: Annual spending on frozen products.
- **Detergents_Paper**: Annual spending on detergents and paper products.
- **Delicassen**: Annual spending on delicatessen products.
- **Channel** and **Region**: Categorical features representing the channel and region of the customer, respectively.

## Methodology
1. **Data Preprocessing**: Scaling numerical features to ensure equal contribution during clustering.
2. **Exploratory Data Analysis**: Analyzing distributions and relationships between features.
3. **Clustering Analysis**:
   - Implementing the Elbow Method to determine the optimal number of clusters.
   - Applying KMeans clustering to segment customers.
   - Using PCA for reducing dimensionality and visualizing the dataset.
4. **Results Interpretation**: Analyzing and interpreting the characteristics of each cluster.

## Conclusion
The analysis provides valuable insights into customer behavior, highlighting distinct segments within the wholesale market. These insights can guide targeted marketing strategies and operational adjustments to better meet customer needs.

## Future Work
Further research could explore combining unsupervised learning with supervised techniques to predict customer behavior and enhance segmentation accuracy.