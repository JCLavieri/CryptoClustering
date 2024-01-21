# Cryptocurrency Market Analysis

## Overview
This project conducts a detailed analysis of cryptocurrency market data using K-Means clustering and Principal Component Analysis (PCA) to identify patterns and groups among various cryptocurrencies.

### Data Source
The data, contained in `crypto_market_data.csv`, includes various performance metrics of cryptocurrencies.

### Technologies
- **Python 3.x**
- **Libraries:**
  - `Pandas` for data manipulation
  - `Scikit-learn` for machine learning (KMeans, PCA, StandardScaler)
  - `Matplotlib` for visualizations

## Analysis Process

1. **Data Loading and Exploration**
   - Load data into a Pandas DataFrame.
   - Perform initial exploration and generate summary statistics.

2. **Data Preprocessing**
   - Normalize data using StandardScaler.

3. **K-Means Clustering**
   - Use the Elbow Method to determine the optimal number of clusters (k).
   - Apply K-Means clustering to the cryptocurrencies.

4. **Principal Component Analysis (PCA)**
   - Reduce dimensionality with PCA.
   - Cluster the data using the PCA-transformed dataset.

5. **Visualization**
   - Create scatter plots to visualize the clusters.
   - Analyze the weightings of PCA components.

6. **Findings and Insights**
   - Identify key features influencing the clusters.
   - Compare clusters in original and PCA-transformed data.

## Results
- The optimal number of clusters (k) was identified as 4.
- PCA provided insights into the impact of different timeframes on clustering.

## Usage
Scripts and notebooks can be used for replicating this analysis or applied to similar datasets.


## License
This project is licensed under the [MIT license](LICENSE).
