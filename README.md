Crypto Currencies
Using Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
App Screenshot

Dependencies and Setup
import pandas as pd
import hvplot.pandas
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
Roadmap
Load the crypto_market_data.csv into a DataFrame.

Get the summary statistics and plot the data to see what the data looks like before proceeding.

App Screenshot

Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

Use the elbow method to find the best value for k

App Screenshot

Cluster Cryptocurrencies with K-means Using the Original Scaled Data
App Screenshot

Find the Best Value for k Using the PCA Data
App Screenshot

Cluster Cryptocurrencies with K-means Using the PCA Data
App Screenshot

App Screenshot
