# Stock Sentiment Analysis using News Headlines

### About the problem and the dataset used:

- The data set in consideration is a combination of the world news and stock price shifts available on Kaggle.
- There are 25 columns of top news headlines for each day in the dataframe.
- Data ranges from 2008 to 2016 and the data from 2000 to 2008 was scrapped from Yahoo finance.
- Labels are based on the Dow Jones Industrial Average stock index.
- Class 1 - the stock price increased.
- Class 0 - the stock price stayed the same or decreased.

### About the approach:

- Used TF-IDF and Bag of Words for extracting featues from the headlines.
- Used Random Forest Classifier, Multinational Naive Bayes and Passive Aggressive Classifier for analysis.
