# nyc_condos_draft
Analysis of condos and their prices in New York City over time.
# pca_and_kmeans_nyc_condos.ipynb
I conducted Principal Component Analysis (PCA) on eight features and performed KMeans clustering to classify the data into three distinct groups.

Principal Component Analysis (PCA):

PC1: Captures variations in Gross SqFt, Estimated Gross Income, Estimated Expense, Net Operating Income, Full Market Value, and Total Units.
PC2: This component mainly reflects variations in Year Built and Report Year.
PC3: Similar to PC2, this component also highlights variations in Year Built and Report Year.
KMeans Clustering:

I utilized KMeans clustering to segment the data into three clusters based on key features such as Total Units, Year Built, Gross SqFt, Estimated Gross Income, Estimated Expense, Net Operating Income, Full Market Value, and Report Year. The clusters are characterized as follows:

Cluster 0: Represents condos with the lowest values in terms of size, expenses, and other financial metrics.
Cluster 1: Represents condos with middle-range values for size, expenses, and financial metrics.
Cluster 2: Represents condos with the highest values, expenses, and size.
This clustering helps in predicting and understanding the distribution of these attributes across different types of condos in NYC.
