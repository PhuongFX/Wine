**Clustering Connoisseurs: A Machine Learning Approach to Wine Classification 🍷**
===========================================================

Are you curious about the science behind wine classification? Do you want to learn how machine learning can help us better understand the complex world of wine? Then you're in the right place! 🎉

> It's like trying to find the perfect wine to pair with your favorite dish, but instead of relying on personal taste, the machine help you to make the match! 🤖

[![License: AGPL-3.0](https://img.shields.io/badge/License-AGPL%203.0-blue.svg)](https://github.com/PhuongFX/ButterFlySpace/blob/main/LICENSE)
[![Python 3.8](https://img.shields.io/badge/python-3.8-blue.svg)](https://www.python.org/downloads/release/python-380/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-1.0.2-green.svg)](https://scikit-learn.org/stable/)
[![Pandas](https://img.shields.io/badge/pandas-1.3.5-red.svg)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-1.21.4-purple.svg)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/matplotlib-3.5.1-pink.svg)](https://matplotlib.org/)
[![Open Source](https://img.shields.io/badge/Open%20Source-%E2%9D%A4-green.svg)](https://opensource.org/)

## `About`
> Clustering Connoisseurs is a machine learning project that uses a comprehensive dataset of 13 chemical constituents of wine to cluster wines into distinct categories.
> > The goal is to develop a system that can accurately classify wines based on their chemical profiles, and provide insights into the characteristics of different wine styles.

## `What's in this project?` 🫶

* A dataset comprising 13 chemical constituents of wine, captures the diverse chemical profiles of wines from the same region in Italy but derived from three different cultivars.
* Machine learning algorithms to classify wines into distinct categories based on their chemical constituents.
* Including interactive visualizations of the wine data to make it easy to explore and understand the relationships between different wine characteristics.
* Model evaluation using classification reports and accuracy scores
* Prediction of cluster assignment of new, unseen wine samples based on their chemical constituents.

## `How it Works` 🫶

Using a combination of exploratory data analysis, data preprocessing, feature scaling, and K-Means clustering to clustering, and 📈visualization to identify patterns and relationships in the wine data.


## `Methodology` 🔍

1. **Exploratory Data Analysis (EDA)**: The dataset is analyzed using various visualizations and statistical methods to identify patterns, outliers, and correlations.
2. **Data Preprocessing**: Applying StandardScaler to the training features. Then finally shuffling dataset to increase randomness and reduce the likelihood of bias in the training process. Outliers are also been considering.
3. **Clustering**: Using K-Means clustering algorithm with the optimal number of clusters determined using the Elbow Method and Hierarchical Clustering.
4. **Evaluation**: Model performance is evaluated using Silhouette Score
5. **Visualization**: 3D scatter plot and a countplot to show the distribution of the clusters.

## `Results` 📊

🎉 Resulting in three clusters of wines with distinct profiles:

* Cluster 1: Low Proline & low Alcohol 🍸
* Cluster 2: Low Proline & average Alcohol 🍹
* Cluster 3: Average Proline & high Alcohol 🍷

Clusters are also visualized using a scatter plot to show the relationship between Proline and Alcohol, and a boxenplot to show the distribution of Color Intensity across the clusters.

## `Usage` 🤗

📝 Here are some example use cases for this project:

* Wine recommendation systems: Used to develop personalized wine recommendations based on a user's taste preferences.
* Wine classification: Used to classify wines into different categories based on their chemical constituents.
* Quality control: Used to identify outliers and anomalies in the wine production process.
