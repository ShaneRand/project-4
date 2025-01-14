# Forecasting Cryptocurrency Prices
## Forecasts made using Bloomberg's price data from 12/31/2019 - 1/1/2025
## Slide presentation:
## Using an LSTM machine model to predict the prices of Bitcoin, Ethereum, and SPY over the next 365 days
Slide Presentation: https://docs.google.com/presentation/d/1CC2Po0kCFion2GMhL2tDt-QxpxxH7qPPQLVvX-93Mws/edit

Why an LSTM Model?
    LSTMs enable recurrent neural networks to recall inputs over a longer period of time
    Normalize the data
    Using a 60 period lookback
    Training 75%, Testing 25%
    Forecasting Future  Prices for next 360 days
    RNNs are a robust and powerful type of neural network and are considered one of the most professional algorithms because they are the only ones with internal memory.

    Long short-term memory networks are an extension of recurrent neural networks, which basically extend the memoryX_train and Y_train will be used to train the LSTM model, while X_test and Y_test will be used to evaluate its performance.

![BTC Training/Testing](https://github.com/ShaneRand/project-4/blob/main/prediction_graphs/bitcoin_prediction.png)


![BTC Forecasting](https://github.com/ShaneRand/project-4/blob/main/prediction_graphs/bitcoin_forecast.png)

![Ethereum Training/Testing](https://github.com/ShaneRand/project-4/blob/main/prediction_graphs/ethereum_prediction.png)


![Ethereum Forecasting](https://github.com/ShaneRand/project-4/blob/main/prediction_graphs/ethereum_forecast.png)

![SPY Training/Testing](https://github.com/ShaneRand/project-4/blob/main/prediction_graphs/spy_prediction.png)


![SPY Forecasting](https://github.com/ShaneRand/project-4/blob/main/prediction_graphs/spy_forecast.png)

Which investment to make?
That depends on your appetite for risk. If you trust the model and can buy BTC or Ethereum at less than the forecasted price, and can accept the riskiness of cryptocurrency, the returns since 2019 are great. Safer assets like SPY (index fund on SP500) or Fidelity's mutual fund, provide adequate returns over the same horizon.

    Assumptions and Limitations
-LSTM models are susceptible to overfitting. 

-LSTMs are often known as "black-box" models, making it difficult to analyze how one arrives at particular decisions.

-LSTs on larger data sets can be very time intesive.

-Complexity: LSTMs have a more sophisticated architecture compared to other RNNs or feedforward neural networks. This complexity can make them more challenging to implement and tune.