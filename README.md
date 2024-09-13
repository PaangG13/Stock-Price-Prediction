# Stock Price Prediction

### Abstract
Develop LSTM models to predict stock prices.

### Data sets
Shanghai Stock Exchange Index (ticker: SSE Composite Index -000001): 10 yeas timeline (from the start of 2013 to the end of 2022). 

(80% training, and 20% testing)

### Method
Using the last 10 days of the closing prices of the stock to predict the closing price of the coming 5th day from now (example as below):

To predict day 15, the input data is [1,2,3,4,5,6,7,8,9,10]

### Accuracy formula
∑ | true value - predicted value | 
