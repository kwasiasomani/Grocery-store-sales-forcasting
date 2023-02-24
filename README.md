# Grocery-store-sales-forcasting




# Introduction
In this project, we are trying to forecasts product sales based on the items, stores, transaction and other dependent variables like holidays and oil prices. This is a Kaggle Competition called "Corporación Favorita Grocery Sales Forecasting" where the task is to predict stocking of products to better ensure grocery stores please customers by having just enough of the right products at the right time. For this particular problem, we have analyzed the data as a supervised learning problem. In order to forecasts the sales we have compared different regression models like Linear Regression, Decision Tree, lightGBM, Random Forest,SARIMA,AR,ARIMA and XgBoost. 
There are 5 additional data files that provide the following information:

-- stores.csv : Details about the stores, such as location and type.

-- items.csv: Item metadata, such as class and whether they are perishable. Note, that perishable items have a higher scoring weight than others.

-- transactions.csv: Count of sales transactions for the training data

-- oil.csv: Daily oil price. This is relevant, because “Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices.” (source)

-- holidays_events.csv: Holidays in Ecuador. Some holidays can be transferred to another day (possibly from weekend to weekday).


