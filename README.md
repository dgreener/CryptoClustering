**Objective**
The aim of this exercise is use unsupervised learning to predict whether cryptocurrency prices are much subject to 24hr or 7 day price fluctuations. 

**Approach**
1) We prepared the data using the StandardScaler() module from scikit-learn to normalize the data.
2) We used the elbow method to find the best value for "k", using the original scaled data.
3) We clustered the cryptocurrencies, for the best value for "k".
4) We then optimized the data, using Principal Component Analysis (PCA), and repeating steps 2 and 3.

**Results**
Using fewer features as part of the PCA optimization, resulted in lower latency and tighter clustering of data, which facilitates analytical comparison between distinct clusters / classes.
   
