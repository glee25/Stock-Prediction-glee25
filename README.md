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

## Prerequisites

### Dataset

You can use any stock data (e.g., AAPL, MSFT, TSLA) obtained from:
  - Yahoo Finance
  - Kaggle

### Installing

1. Cloning Git Repository
```
git clone https://github.com/glee25/stock-prediction-glee25.git
cd stock-prediction-glee25
```

2. Create a Virtual Environment
```
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate
```

3. Install Dependencies
```
pip install -r  
```

## Running the tests


### Data

```
Give an example
```

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

* **Gerald Lee** - *Initial work* - [Glee25](https://github.com/glee25)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
