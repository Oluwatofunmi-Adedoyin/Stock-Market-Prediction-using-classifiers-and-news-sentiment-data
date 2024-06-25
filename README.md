# Stock-Market-Prediction-using-classifiers-and-news-sentiment-data
An attempt to measure the impact of sentiment analysis data on the accuracy of stock market predictions using machine learning algorithms
This study seeks to certify if market sentiment analysis improves the accuracy of stock market predictions. If it does, how significant this impact is, and if it is worth the extra investment. 

The Null hypothesis for this study is: that market sentiment analysis has no impact on the accuracy of stock market predictions

The data used in this study includes stock market data obtained from the yfinance package. Technical indicators were computed on the stock data obtained from yfinance using the pandas_ta library in Python.

Financial news sentiment data was gathered using EODHD APIs financial news sentiment API. The API provided the normalized sentiment score of various new articles for each day in the timeframe of the study

In this experiment, I sought to predict whether the market would close higher or lower than the previous day and not predict price. Therefore, for the experiment, several classifiers were used.
