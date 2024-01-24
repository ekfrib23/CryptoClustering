# CryptoClustering
## Motivation
This project uses data in Resources/crypto_market_data.csv to make predictions on cryptocurrencies using the K-means model and the principal component analysis. The data was normalized to reduce the influence of large values before the calculating the biggest percentage change in order to determine the best value for k or the number of clusters. The clustering was examined for the price change percentage for 7 days vs 24 hours graphically.  From the plot, it appears that the 2 largest clustering can be found above or below around the 0 mark in the 7 day percentage change.  

In the principal component analysis, using three components captures 89.5 percent of the data. In the 4 clustering K-means model, it appears that the 2 largest clustering can be found above or below around the 0 mark in the PCA2 and mostly has a negative influence for PCA1.

The price_change_percentage_7d has the strongest influence on PCA3 at +78.8%.The price_change_percentage_24h and price_change_percentage_60d has the strongest negative influences on PCA3. This is 1/2 the positive influence at -36.1% and -21.9%, respectively.

The price_change_percentage_14d and price_change_percentage_30d have the strongest positive influences on PCA2 at 54.0% and 56.2% respectively. The price_change_percentage_1y is the only negative influence, which is about 1/4 the value of the strongest positive influences

The price_change_percentage_200d and price_change_percentage_1y have the strongest positive influence of 59.4% and 56.8%, respectively and price_change_percentage_24h has the strongest negative influence equal to -41.7% on PCA1

