# Cryptocurrencies

## Project Overview
This project is to classify and group cryptocurrencies on the trading market for further investment analysis by adopting unsupervised machine learning and K-Means model. Basically, these are steps I make to train the model and make predictions:

- First, preprocess the data by handing data types, drop nulls and unwanted columns, label string data to numeric data by using one-hot coding, and standard scale the data. After the cleaning and preparing, 531 unique cryptocurrencies in total will be avaiable to use.
- Then, use PCA to reduce dimensions of data and fasten the speed of running a model.
- Thrid, call the K-Means model to cluster cryptocurrencies. To find the best value of K, I introduce the elbow curve and the result shows that the most suitable value is 4.
- Fourth, visualize the cryptocurrencies results with hvplot. The 3d-scatter plot illustrates four clusters in crpytocurrencies, the table contains all the information of tradeable crpytocurrencies, and the 2d-scatter plot demonstrates each currency's supply and mined amount.


## Result
![3d_scatter_with_clusters](https://github.com/ZiwenLyu/Cryptocurrencies/blob/main/3d_scatter_with_clusters.png)

![tradeable_crpytocurrencies](https://github.com/ZiwenLyu/Cryptocurrencies/blob/main/tradeable_crpytocurrencies.png)

![scatter_mined_supply](https://github.com/ZiwenLyu/Cryptocurrencies/blob/main/scatter_mined_supply.png)
