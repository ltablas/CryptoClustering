# CryptoClustering

This week's challenge is on finding best value of k using a variety of methods. 

Raw data comes from 'crypto_market_data.csv' file in Resources folder and loaded as a DataFrame in Jupyter notebook 'Crypto_Clustering.ipynb'. 

1) The first method to find best value of k is with using StandardScaler and Scaled DataFrame to plot an Elbow Curve. Based on the elbow visualization of the scared data, it appears the best value of k is 4.
A scatter plot of the data was then created to visualize the 4 clusters.

2) Second method used to find best value of k is with PCA, and reducing the features to 3 principle components. Objective is to see if reducing the features gives similar results as using full scaled data.
Best value for k using PCA data still appears to be 4. Scatter plot also shows 4 distinct clusters.

Based on composite plots at the end of the notebook, one can conclude that for this dataset, reducing the features to determine best value of k was effective as it provided same results while using less data/processing.