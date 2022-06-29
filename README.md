# Cryptocurrencies

## Purpose of analysis

We are analyzing the Cryptocurrencies dataset and group them by clustering algorithm using unsupervised machine learning. 

We first process the data, reduce our dimensions and NaN, reduce the principal components using PCA. At the end we will use data visualizations.


## Resources

Dataset: [CryptoCompare](https://min-api.cryptocompare.com/data/all/coinlist)

Software: Python 3.10, Conda 4.13, jupyter notebook 6.4.11

## Result

- Elbow Curve - we used elbow curve by K-Means method iterating on k values from 1 to 10

![bokeh_plot](https://user-images.githubusercontent.com/100378319/176551362-a742d5f2-6f68-49ba-87af-4ee6ac1551ac.png)

We can see that point 4 is the best output to categorize the crytocurrenies

- 3D Scatter Plot with Cluster 

![3d](https://user-images.githubusercontent.com/100378319/176551473-d3d77d2d-4cfb-4c84-bac1-87fbeac18ed9.png)


After applying PCA algorithm and we obtained 3 principal components and we produced a 3D scatter plot


- hvTable - it displays all currently tradeable crytocurrencies

![hv](https://user-images.githubusercontent.com/100378319/176551504-db4ec906-3f0c-4eb4-858b-e3943e07079a.png)

- hvPlot - The graph is a scatter plot grouped by 4 classes. 

![2](https://user-images.githubusercontent.com/100378319/176551517-0cce1ee2-494a-477e-ad60-7ce6661f38dc.png)


## Summary

There are 532 crytocurrencies based on their similarities. This report can be used by investment company or the bank to create a new investment portfolio or have a deeper analysis.

