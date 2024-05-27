# Stock Sentiment Analysis using News Headlines

## Data Preparation
- Loaded the dataset and split it into training and testing sets.
- Removed punctuations and converted headlines to lowercase.

## Feature Extraction
- Used CountVectorizer to implement the Bag of Words model with bigrams.

## Model Training
- Trained a RandomForest Classifier with 200 estimators using the training data.

## Model Evaluation
Confusion Matrix:
 [[138  48]
 [  7 185]]
Accuracy Score: 0.8544973544973545
Classification Report:
               precision    recall  f1-score   support

           0       0.95      0.74      0.83       186
           1       0.79      0.96      0.87       192

    accuracy                           0.85       378
   macro avg       0.87      0.85      0.85       378
weighted avg       0.87      0.85      0.85       378

## Buy/Sell Signal Generation
- Generated buy and sell signals based on the sentiment predictions using moving crossover startegy.

## Portfolio Returns and Performance Metrics
Moving Average Strategy:
Sharpe Ratio: 1.585533826042266
Maximum Drawdown: -0.2849368491361862
Number of Trades Executed: 17
Win Ratio: 0.23529411764705882

## Plot
- Plotted the stock price with buy and sell signals
- 
