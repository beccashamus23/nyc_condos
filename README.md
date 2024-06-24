# nyc_condos_draft
Analysis of condos and their prices in New York City over time.

# linear_regression_model_analysis_nyc_condos.ipynb
The Random Forest model yielded cross-validation scores of [0.415, 0.405, 0.44, 0.3919598, 0.4120603], indicating consistent performance across different folds.

To further explore the relationship between features and income, the Ordinary Least Squares (OLS) regression model an R-squared value of 0.202, suggesting that approximately 20.2% of the variability in income is explained by the model. The adjusted R-squared, which accounts for the number of predictors in the model, was slightly lower at 0.134. This implies that the model's explanatory power diminishes when adjusted for the number of predictors.

The OLS regression results also include a significant F-statistic of 2.948, with a p-value of 1.14e-14, indicating that the model as a whole is statistically significant. Despite this, the model's intercept was not statistically significant, with a t-value of -0.887 and a p-value of 0.375, suggesting that the intercept does not contribute meaningfully to the model.

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
