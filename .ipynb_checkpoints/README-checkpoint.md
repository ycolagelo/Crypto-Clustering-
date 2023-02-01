# Crypto-Clustering (Machine Learning)
![Image](10-5-challenge-image.png)

# Analyzing and clustering data using scaled data and Principle Analysis Data

---

### Proposing a novel approach to assembling investment portfolios that are based on cryptocurrencies. Instead of basing the proposal on only returns and volatility, I want to include other factors that might impact crypto market leading to better performance for my portfolio.


## Visual analysis for the data
![Image](bokeh_plot_line.png)

* I find the best value for the clusters(k) for the scaled data using the elbow method and visualize the data 
![Image](bokeh_plot_elbow_scaled.png)

* Using the data, I cluster cryptocurrencies with K-Means 
![Image](bokeh_scatter_scaled.png)

* I optimise clusters with Principal Component Analysis, condensing the data to 3 components and  use the elbow method to find the best value for clusters(k)
![image](bokeh_plot_pca.png)

* A new dataframe is created with the Principle Analysis Data and used to plot the clusters.
![image](bokeh_plot_pca_scatter.png)

#### Answer the following question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Question:** After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?

  * **Answer:** # Using fewer features reduces noise which allows for proper distribution of the clusters