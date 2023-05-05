Bitcoin_Price_Predictor

    
We'll predict the future price of Bitcoin using historical price and sentiment data.  We'll use data on the USD/BTC price from Yahoo Finance, along with data from Wikipedia about edits to the Bitcoin page.  

We'll merge and combine this data, then use it to train a random forest model that will tell us if Bitcoin prices will increase or decrease tomorrow. We'll then switch to an XGBoost model and better predictors to improve accuracy.

We'll develop a backtesting system and use a robust error metric so we can tell if the algorithm is performing well.  This system will also be able to make next-day predictions.

This project can be extended to other cryptocurrencies, or be used to predict multiple days ahead.
