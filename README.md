# Stock-Prediction-glee25

This open-source project will showcase how combining ARIMA (AutoRegressive Integrated Moving Average) and LSTM (Long Short-Term Memory) models can possibly improve the accuracy of stock price predictions.
By leveraging both statistical time-series modeling (ARIMA) and deep learning sequence modeling (LSTM), we can capture linear and non-linear dependencies in stock data—leading to more robust forecasts.

## Overview

While ARIMA models are excellent at modeling linear trends, they often fail to capture non-linear market patterns. LSTM neural networks, on the other hand, excel at recognizing complex non-linear 
relationships but may struggle with stationary assumptions and long-term seasonality.

This project proposes a hybrid ARIMA-LSTM pipeline:
  - Use ARIMA to model and remove the linear component of the stock price time series.
  - Use LSTM on the ARIMA residuals to learn non-linear patterns.

Combine both predictions for a final, more accurate forecast.

## Authors

* **Gerald Lee** - *Initial work* - [Glee25](https://github.com/glee25)

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE.md](LICENSE.md) file for details
