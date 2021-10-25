# Cryptocurrencies

## Overview of Analysis
Given a list of available cryptocurrencies and information such as algorithm(s) used, trading status, total coins mined and total coin supply; use unsupervised machine learning to group the cryptocurrencies into distinct and useful classifications.

### Resources used
- pandas
- hvplot
- plotly.express
- sklearn.preprocessing - StandardScaler, MinMaxScaler
- sklearn.decomposition - PCA
- sklearn.cluster - KMeans

## Results 
Data started with 1144rows, 459 rows were dropped for missing data, another 153 dropped for not having a number 0 or larger in the TotalCoinsMined column. This cleaned data then combined into three principal compensents using PCA, then into 4 distinct clusters using K-means. Further testing and analysis needed to assess what makes the data within these 4 clusters coorelated. BitTorrent however, does stand out as it is in a cluster by itself. 
