# Stock-Market-Prediction



1. we are going to retrieve and scrape data from the yfinance (yahooo financial API) and train the model using a snapshot of the specific stock trend.

2. scale the data

scaler = StandardScaler()
df['Close'] = scaler.fit_transform(df['Close'])