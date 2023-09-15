# [Stock Price Prediction using Python and the LSTM Machine Learning Model](https://github.com/PrashanthReddy47/StockPricePrediction_LSTM/blob/main/StockPricePrediction_LSTM.ipynb)
- In this project, we use Python and the LSTM machine learning model to predict the stock price of TSLA (Tesla, Inc.). We start by importing the necessary libraries and creating a Ticker object for TSLA. We then visualize the closing price and create a new data frame with only the close column. This data frame is converted to a numpy array and scaled using a MinMaxScaler.
- We then split the scaled data into training and testing datasets, which are then converted to numpy arrays. An LSTM model is built and compiled, and is then trained on the training data. The model is used to make predictions on the testing data, and the performance of the model is evaluated using various evaluation metrics. The results are visualized and the model is used to predict the stock price of TSLA on the next trading day.
- Overall, this project demonstrates how machine learning can be used to predict stock prices and provides a step-by-step guide for implementing this approach using Python and the LSTM model.

![Correlation]( https://github.com/PrashanthReddy47/StockPricePrediction_LSTM/blob/main/Results/Final_Result.png?raw=true)

# Installation Instructions
## To use this project, you will need to have Python and the following libraries installed:

- 	yfinance
-	pandas
-	numpy
-	matplotlib
-	keras

## Installation


You can install these libraries using pip:
```sh
pip install yfinance pandas numpy matplotlib keras 
```
## Usage Instructions

To use this project, follow these steps:
1.	Clone the repository to your local machine using Git.
2.	Navigate to the local repository on your machine.
3.	Open the StockPricePrediction_LSTM.ipynb file in a text editor or Python IDE.
4.	Set the ticker variable to the stock ticker you want to predict the price for.
5.	Run the script to train the LSTM model and make predictions.

## Dependencies
This project relies on the following libraries:
-	yfinance, pandas, numpy, matplotlib, keras

### Make sure these libraries are installed before running the script.

"This project was completed following the tutorial at https://www.youtube.com/watch?v=QIUxPv5PJOY&ab_channel=ComputerScience by Computer Science on YouTube. Thank you to Computer Science for sharing their knowledge and expertise in this video."


