![cover_photo](https://github.com/dplem/Cryptocurrency-Price-Prediction/blob/main/Wordcloud/Bitcoin.png)

# Cryptocurrency-Price-Prediction

Derek Plemons
Springboard Data Science Career Track

Capstone Project 2

### Problem Statement:

Using the comments of the r/Bitcoin subreddit and the historical bitcoin price, can we predict whether the price of bitcoin will decrease or increase for the following day?

### Background:

The price of Bitcoin and many other cryptocurrencies has been historically, very volitile. If there was a way to forecast the upward or downward trend of the market even to a few percentage points above random, it could be extrememly valuable. If the market is a reflection of peoples buying power, could it not be possible to predict the market using individuals sentiment about a product, in this case, Bitcoin? 

While being able to predict the market patterns for cryptocurrency would be useful, we can also evaluate which social media platform is most reflective of actual market sentiment. In other words, which social media platform is useful. it will also be interesting to see what are the capabilities of machine learning tools to make such predictions.

### Data Sources:

1. Reddit Pushshift API - Used to collect historical r/bitcoin subreddit comments for everyday from 12/31/2019 to present
2. Bitcoin Historical Price - Used the Historical-crypto api to create bitcoin price dataset by date

### Features:

Pushshift API Comment Data:

· 41 Columns   
· Author - unique author of comment   
· Date - date of submitted comment   
· Body - comments submitted by user   
· Total Comments - 1.6 million   

Historical Bitcoin Price:

· Date - Date of historical price   
· Closing Price - closing price of bitcoin by date   
 
### Objectives:

1. Use Pushshift API data from r/bitcoin subreddit to calculate sentiment scores by day
2. Use historical bitcoin price by day and merge with r/bitcoin subreddit to predict whether bitcoin price will go up or down for following day
3. Use Logistic Regression, K Nearest Neighbors, Support Vector Machine, Random Forest and Gradient Boosting for classification

Reports:

1. [Data Collection Notebook](https://github.com/dplem/Cryptocurrency-Price-Prediction/blob/main/Notebooks/1_Data_Collection.ipynb)
2. [Data Exploration Notebook](https://github.com/dplem/Cryptocurrency-Price-Prediction/blob/main/Notebooks/2_Exploratory_Analysis.ipynb)
3. [Feature Engineering Notebook](https://github.com/dplem/Cryptocurrency-Price-Prediction/blob/main/Notebooks/3_Feature_Engineering.ipynb)
4. [Modeling Notebook](https://github.com/dplem/Cryptocurrency-Price-Prediction/blob/main/Notebooks/4_Modeling.ipynb)
5. [Final Report](https://github.com/dplem/Cryptocurrency-Price-Prediction/blob/main/Reports/Cryptocurrency%20Market%20Prediction%20Report.pdf)
6. [Final Presentation](https://github.com/dplem/Cryptocurrency-Price-Prediction/blob/main/Reports/Cryptocurrency%20Price%20Prediction%20Presentation.pdf)
