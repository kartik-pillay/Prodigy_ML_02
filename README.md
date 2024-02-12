# Mall Customer Segmentation

## Overview

This project explores and analyzes customer data from a mall using various visualization techniques and applies K-Means clustering to segment customers based on their annual income and spending score. The project aims to understand patterns and provide insights into customer behavior.

## Table of Contents

- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [K-Means Clustering](#k-means-clustering)
- [Results](#results)
- [Conclusion](#conclusion)

## Dataset

The dataset used in this project is named 'Mall_Customers.csv' and contains information about customers, including age, annual income, and spending score.

## Exploratory Data Analysis

The project begins with data exploration using visualizations to understand the distribution of age, annual income, and spending score. Gender distributions are also analyzed, and relationships between different features are visualized.

## K-Means Clustering

K-Means clustering is employed to segment customers into distinct groups based on their annual income and spending score. The optimal number of clusters is determined using the elbow method and silhouette scores.

## Results

The final K-Means model with 5 clusters is applied, and the results are visualized. The centroids of each cluster are plotted on the scatter plot of annual income vs. spending score. Additionally, the average values of annual income and spending score for each cluster are presented in a bar chart.

## Conclusion

The project concludes by summarizing the key findings and insights gained from the analysis. It provides a high-level overview of customer segmentation and its potential applications for business strategy.

## Dependencies

- pandas
- matplotlib
- seaborn
- plotly
- scikit-learn
- xgboost

## How to Run

1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script.

Feel free to contribute, report issues, or provide feedback! at pillaykartik01@gmail.com
