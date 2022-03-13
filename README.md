# Cryptocurrencies

Unsupervised learning, K-means algorithm and using principal component analysis (PCA)

### Overview of the analysis: Explain the purpose of this analysis.

Unsupervised learning is used for, how to process data, how to cluster, how to reduce your dimensions, and how to reduce the principal components using PCA. we're going to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for the new investment. The data we will be working with is not ideal, so it will need to be processed to fit the machine learning models. Since there is no known output for what we are looking for, we decided to use unsupervised learning. To group the cryptocurrencies, we decided on a clustering algorithm. we’ll use data visualizations to share her findings with the board.

- Preprocessing the Data for PCA
- Reducing Data Dimensions Using PCA
- Clustering Cryptocurrencies Using K-means
- Visualizing Cryptocurrencies Results

### Results:

Using the Principal Component Analysis (PCA) algorithm to reduce the dimensions of the X DataFrame to three principal components and place these dimensions in a new DataFrame.

![This is an image](pic1.png)

Using the K-means algorithm, to create an elbow curve using hvPlot to find the best value for K from the pcs_df DataFrame. Then, run the K-means algorithm to predict the K clusters for the cryptocurrencies’ data.

![This is an image](pic2.png)

Create a 3D scatter plot using the Plotly Express scatter_3d() function to plot the three clusters.

![This is an image](pic3.png)

Create a table with tradable cryptocurrencies using the hvplot.table() function.

![This is an image](pic4.png)

Then, Create an hvplot scatter plot with x="TotalCoinsMined", y="TotalCoinSupply", and by="Class", and have it show the CoinName when you hover over the the data point.

![This is an image](pic5.png)

### Summary:

