# ML_Clustering_Crypto
Use Unsupervised Machine Learning to group and classify Crypto Tokens.

### Background 
This project was to provide insight into how an investment firm like BlackRock or Fidelity might classify Crypto Tokens to for decisions related to which they might invest in themselves or provide to their retail customers.

### Resources
- Data: crypto_data.csv
    - Retrieved from https://min-api.cryptocompare.com/data/all/coinlist
- Software: Jupyter Notebook, Python 3.9, Pandas, Plotly, hvPlot, skLearn

### Code
Please view the [Jupyter Notebook](https://github.com/Bag0niku/ML_Clustering_Crypto/blob/main/Crypto_Clustering.ipynb) for preprocessing, PCA, KMeans, and Visualizations.

## Results:
### Visualizing the K-means clustering algorithm provided the following output:    
![3d Cluster plot](/Images/3d_cluster_2.png)

### When you used those grouping results and apply them to the "total coins mined" vs "total coin supply" scatter plot you get:
![scatter plot](/Images/supply_scatter_1.png)

### Those 2 outliers make the rest of the graph harder to see, lets zoom in on the clump.
![zoomed scatter plot](/Images/supply_scatter_zoom.png)


## Next Steps:
- Investigate what the realtionship of those 4 groups are, what Tokens are in them, and what seperates them. The computer told me they are related, but now I have to figure out how.

