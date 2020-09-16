# LSTM Stock Predictor

In this project we are comparing which feature gives us the best prediction of the nth day price of Bitcoin using the LSTM RNN model.

The two features are:
* Fear and Greed value
* Prices of days 0 to n-1

[lstm_stock_predictor_closing.ipynb](lstm_stock_predictor_closing.ipynb) contains the notebook where we used closing prices for days 0 to n-1 as a feature

[lstm_stock_predictor_fng.ipynb](lstm_stock_predictor_fng.ipynb) contains the notebook where we used Fear and Greed value as a feature

### To evaluate the performance of each model we answer the follwoing questions:


* Which model has a lower loss?
    * The model using the closing price as the feature had the lowest loss

* Which model tracks the actual values better over time?
    * The model using the closing price tracks the values a lot better based off the plot

* Which window size works best for the model?
    * I found that the window size of 10 gave the best results
