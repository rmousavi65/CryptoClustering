
#  Crypto Currencies

- Using Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

![App Screenshot](https://raw.githubusercontent.com/gnimeth/Cryptoclustering/main/Outputs/closeup-golden-usd-coins-dropping-dark-background-dollar-is-main-currency-exchange-payment-world-by-3d-render.jpg)
## Dependencies and Setup

```bash
import pandas as pd
import hvplot.pandas
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```


## Roadmap
- Load the crypto_market_data.csv into a DataFrame.

- Get the summary statistics and plot the data to see what the data looks like before proceeding.

![App Screenshot](https://raw.githubusercontent.com/gnimeth/Cryptoclustering/main/Outputs/bokeh_plot.png)

- Use the StandardScaler() module from scikit-learn to normalize the data from the CSV file.

- Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

- Use the elbow method to find the best value for k

![App Screenshot](https://raw.githubusercontent.com/gnimeth/Cryptoclustering/main/Outputs/bokeh_plot%20(1).png)

- Cluster Cryptocurrencies with K-means Using the Original Scaled Data

![App Screenshot](https://raw.githubusercontent.com/gnimeth/Cryptoclustering/main/Outputs/bokeh_plot%20(2).png)

- Find the Best Value for k Using the PCA Data

![App Screenshot](https://raw.githubusercontent.com/gnimeth/Cryptoclustering/main/Outputs/bokeh_plot%20(3).png)

- Cluster Cryptocurrencies with K-means Using the PCA Data

![App Screenshot](https://raw.githubusercontent.com/gnimeth/Cryptoclustering/main/Outputs/bokeh_plot%20(4).png)


![App Screenshot](https://raw.githubusercontent.com/gnimeth/Cryptoclustering/main/Outputs/bokeh_plot%20(5).png)






