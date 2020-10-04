# Cryptocurrencies

For this challenge, I used the cryptocurrency data in order to perform data processing tasks and remove unnecessary data such as following:
  1. Null values
  3. Columns that were not necessary for the analyzation.
  3. Cryptocurrencies without coins mined, etc.

Also, created dummies variables for all text features and used StandardScaler from sklearn to standarize all of the remaining data.

After data processing, I used PCA algorithm from sklearn in order to reduce  the dimensions of the dataframe down to three principal components: PC1, PC2 and PC3. Then used KMeans algorithm from sklearn to cluster the cryptocurrencies using the PCA data. 

Finally, I created data visualizations to present the final results, 2 and 3D- scatter plots and a table using Plotly Express and hvplot.
