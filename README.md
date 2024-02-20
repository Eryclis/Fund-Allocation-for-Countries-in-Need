# Fund Allocation for Countries in Need

## Overview
This project focuses on using unsupervised learning techniques to cluster countries based on their socioeconomic indicators. The goal is to provide insights to policymakers, NGOs, and governments to allocate funds to countries most in need.

## Dataset
The dataset used in this project contains socioeconomic indicators for countries around the world. It includes features such as GDP per capita, infant mortality rate, life expectancy, etc. The data was obtained from Kaggle and was cleaned/preprocessed before analysis.

## Methodology
### Exploratory Data Analysis (EDA)
- Conducted comprehensive EDA to understand the distribution and relationships between variables.
- Visualized key features and explored correlations using plots and charts.

### Preprocessing
- Performed data preprocessing steps such as handling missing values, feature scaling, and encoding categorical variables.

### Feature Engineering
- Scale the features to ensure uniformity.
- Perform PCA (Principal Component Analysis) to reduce dimensionality.

### Clustering Techniques
- Applied various clustering algorithms including K-means, DBSCAN, and hierarchical clustering.
- Evaluated clustering performance using metrics such as Silhouette Score, Davies-Bouldin score, and Calinski-Harabasz score.

## Results
- **K-means Performance:**
  - Silhouette Score: 0.332
  - Davies-Bouldin Score: 1.133
  - Calinski-Harabasz Score: 85.015


## Conclusion
The clustering analysis revealed distinct clusters of countries based on their socioeconomic characteristics. These insights can inform decision-makers on where to allocate resources effectively.

## Usage
- Clone the repository to your local machine.
- Install the necessary dependencies (Python libraries, Jupyter Notebook).
- Run the Jupyter Notebook files in sequential order to reproduce the analysis.
- Explore the code and visualizations to gain insights into the clustering results.
- Refer to the documentation for detailed explanations of each step.

## Contributors
- Eryclis Rodrigues Bezerra Silva

