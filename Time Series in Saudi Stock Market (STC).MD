
![2795101-455135492](https://user-images.githubusercontent.com/47127790/148238809-fae4be24-038c-4e84-aa4b-74f7f5420816.jpg)

                                       
                                       
                                       SAUDI TELECOM COMPANY(STC) IN STOCK MARKET BY USING TIME SERIES

# Abstract:

 Stock Market Analysis and Prediction is the project related to exploratory data analysis (EDA), data visualization 
and Predictive analysis using data, provided by Saudi stock market companies. It is collected from Saudi Stock 
Exchange (Tadawul). Tadawul is the Saudi Exchange is a fully owned subsidiary by Saudi Tadawul Group. As Saudi 
Arabia’s dedicated stock exchange and the largest stock exchange in the Middle East.

# Design
The objective is to study the behavior of STC company in the saudi stock market, And predict the price for a company in the next two years.
All data used in this project from https://www.saudiexchange.sa/ by using web scraping.

# Data

The dataset’s purpose is to display a list of Tadāwul Platform from Janurary 2012 till November 2021 (up to date) , 
measured by several Measurement such as Date ,close ,open ,Company Name,Value Traded (SAR) and so much more . 
The data was huge it contains a daily captures for 202 compines in the saudia stock market.
For our work, we did a web scrapping to the tadawul website through a private subscibed user.
Data size 2269 of rows. In this project we focused on Close price for each day.


# Algorithms

Stage I: Prepossessing
1. Collect data
EDA
• Cleaning
• Preparing data

Stage I: Prepossessing
1. Collect data
EDA
• Cleaning
• Preparing data
3. Split raw data for testing
▪ Train set (80%) 
▪ Test set t (20%) 
Stage II:Using time ser
1. Split traning set for validation
  Train set (80%) 
  Test set t (20%) 
3. Split raw data for testing
▪ Train set (80%) 
▪ Test set t (20%) 
Stage II:Using time ser
1. Split traning set for validation
  Train set (80%) 
  Test set t (20%) 
4.Import Autoregressive integrated moving average (ARIMA)
5.Import facebook prophet.
6. After that, Choose the best model based on highest R_Squared or lowest error 
 Stage 3: Testing
1. Fit best model.
2. Predict. 
3. Calculate model accuracy.

# Tools
Numpy, Pandas, Matplotlib, Seaborn, ARIMA, facebook prophet,sklearn.metrics,mean_squared_error, mean_absolute_error, and warnings.
