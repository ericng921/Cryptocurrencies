# Cryptocurrencies

## Purpose of analysis

We are analyzing the Cryptocurrencies dataset and group them by clustering algorithm using unsupervised machine learning. 

We first process the data, reduce our dimensions and NaN, reduce the principal components using PCA. At the end we will use data visualizations.


## Resources

Dataset: [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

Software: Python 3.10, Conda 4.13, jupyter notebook 6.4.11

## Result

- Elbow Curve - we used elbow curve by K-Means method iterating on k values from 1 to 10

We can see that point 4 is the best output to categorize the crytocurrenies




- 3D Scatter Plot with Cluster - 


After applying PCA algorithm and we obtained 3 principal components and we produced a 3D scatter plot





- hvTable - it displays all currently tradeable crytocurrencies



- hvPlot - The graph is a scatter plot grouped by 4 classes. 

## Summary

There are 532 crytocurrencies based on their similarities. This report can be used by investment company or the bank to create a new investment portfolio or have a deeper analysis.

