# Cryptocurrencies
## Overview
The goal of this challenge was to utilize unsupervised machine learning to analyze cryptocurrencies and the trends.
## Review
With the cryptocurrency dataset, I preprocessed the date for PCA, dropped columns, and cleaned the dataframe.
* For the PCA, I was able to reduce the dimension into 3 principal components.

![PCA](https://user-images.githubusercontent.com/104965708/200703761-25b264c1-571a-40c4-8f08-e803155d38d5.png)

* First clustering done on the data was the K means and viewing the elbow curve.

![Elbow](https://user-images.githubusercontent.com/104965708/200703838-d8f60c5f-a4e5-4a3e-b70c-92e6de9ed5d3.png)

* Next visualization I generated was the 3D Scatter with Clusters.

![3D](https://user-images.githubusercontent.com/104965708/200703881-c07cce55-da64-490e-8c1a-a9caa6059cbc.png)

* I then created a clusterd hvplot of the tradable cryptocurrencies.

![clustered](https://user-images.githubusercontent.com/104965708/200703989-6126bc0c-a0c7-4aa8-bd0a-d2238f368769.png)

* Final visualization I completed was an hvplot scatter.

![scatter](https://user-images.githubusercontent.com/104965708/200704043-2453ff36-f77a-4fe7-8a7f-9d95e6a4db50.png)
