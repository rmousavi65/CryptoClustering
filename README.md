Crypto Currencies

* Using Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

* ![image](https://github.com/rmousavi65/CryptoClustering/assets/124542074/0e0a85ed-cb9b-4ad9-a391-1548513e5ad7)
  



import pandas as pd

import hvplot.pandas

from sklearn.cluster import KMeans

from sklearn.decomposition import PCA

from sklearn.preprocessing import StandardScaler

Roadmap
Load the crypto_market_data.csv into a DataFrame.

Get the summary statistics and plot the data to see what the data looks like before proceeding.
![image](https://github.com/rmousavi65/CryptoClustering/assets/124542074/df5f4efb-c314-457d-b66d-3480fbc107b4)

Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

Use the elbow method to find the best value for k
![image](https://github.com/rmousavi65/CryptoClustering/assets/124542074/0be36bcd-c9e9-41cd-9fec-985b0e73d225)

Cluster Cryptocurrencies with K-means Using the Original Scaled Data
![image](https://github.com/rmousavi65/CryptoClustering/assets/124542074/c4561922-6c65-4066-b602-5d64db57bab1)

Find the Best Value for k Using the PCA Data
![image](https://github.com/rmousavi65/CryptoClustering/assets/124542074/ad6add8b-817b-4449-983b-0e51c753dbd8)
Cluster Cryptocurrencies with K-means Using the PCA Data
![image](https://github.com/rmousavi65/CryptoClustering/assets/124542074/a1afad69-0a7f-43fd-a657-5cba56a1675c)
![image](https://github.com/rmousavi65/CryptoClustering/assets/124542074/9fcc2905-f60d-4aa8-ad26-48c1098e6f7f)
