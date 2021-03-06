# Stock-Predictor-LSTM


Due to the volatility of cryptocurrency speculation, investors often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the Crypto Fear and Greed Index (FNG) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. I have built and evaluated deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

![dl](https://user-images.githubusercontent.com/86626839/143320758-aa5d774c-f58b-4557-95e4-59718bd290a5.jpg)



In this repository, I have used deep learning recurrent neural networks to model bitcoin closing prices. One model will use the FNG indicators to predict the closing price while the second model will use a window of closing prices to predict the nth closing price.
