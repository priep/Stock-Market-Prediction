# Stock-Market-Prediction

**Project Overview**

This project aims to predict the future prices of the S&P 500 stock market index using historical data fetched via YFinance. The S&P 500 is a key index representing the performance of 500 major companies listed in the US stock exchanges. This project applies machine learning techniques to predict stock prices and help investors understand potential trends in the market.

In this project, the model leverages the Random Forest Classifier, a popular machine learning algorithm, to predict whether the price will increase or decrease based on past trends.

**Project Steps**

1. Download data using the yfinance package
2. Create an initial machine learning model and estimate accuracy
3. Build a backtesting engine to more accurately measure accuracy
4. Improve the accuracy of the model

**Features**
1. Fetch historical stock data of the S&P 500 using the yfinance API.
2. Preprocessing and feature engineering on historical data.
3. Training a Random Forest Classifier to predict stock price movements.
4. Performance evaluation using accuracy,prediction score and other metrics.

**Dataset**

The data is sourced using yfinance, which provides up-to-date and historical financial data.

The data includes features such as:
1. Open: Opening price of the stock index.
2. Close: Closing price of the stock index.
3. High: The highest price of the day.
4. Low: The lowest price of the day.
5. Volume: Number of shares traded.

**Requirements**
The project requires the following Python libraries:
1. yfinance (for fetching historical stock data)
2. pandas (for data manipulation)
3. numpy (for numerical computations)
4. scikit-learn (for building and evaluating the machine learning model)


**How to run the Project**
1. Install Dependencies
2. Fetch Data Using yfinance
3. Preprocess Data and Extract Features
4. Train and Evaluate the Model
5. Make Predictions

**Result**

The model will output whether the next day’s S&P 500 price will increase or decrease.
