# Cryptocurrencies
Unsupervised machine learning techniques to analyze cryptocurrency data.

## Project Overview
This project uses machine learning to identify which cryptocurrencies are on the trading market and to better understand how cryptocurrencies should be grouped to create classifications for developing an investment product. Unsupervised machine learning was chosen used since there is no known output for what I'm looking for. To group the cryptocurrencies, a clustering algorithm was also chosen to help determine whether or not I should be investing in this product.

# The Steps

* Prepare the data for dimensions reduction with PCA and clustering using K-means.
* Reduce data dimensions using PCA algorithms from sklearn.
* Predict clusters using cryptocurrencies data using the K-means algorithm form sklearn.
* Create some plots and data tables to present the clustering results.

## Visulization

* The first visualization that was made was  elbow curve to determine the cluster count

![elbow](https://user-images.githubusercontent.com/90945875/150571148-c30faf6f-cebd-4358-8e6e-c57a483d665e.PNG)

* The second one was combined and a 3D-scatter plot was made with the PCA data and the clusters

![3D-scatter](https://user-images.githubusercontent.com/90945875/150571725-3d0e8a2b-3186-4004-9bed-0e6132b91cdd.PNG)

* The last one a hvplot.scatter plot was created using x=TotalCoinsMined and y=TotalCoinSupply

![hvplot scatter](https://user-images.githubusercontent.com/90945875/150572275-d7300ae6-2469-4ee1-9c6b-fc17d41e37d8.PNG)


