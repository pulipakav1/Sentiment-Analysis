"# Sentiment-Analysis" 

This project implements sentiment analysis on drug reviews using logic regression model. The model classifies reviews into three categories: positive, neutral, and negative, based on user ratings.

#DATASET
-drug_review_test.csv. (https://www.kaggle.com/code/habibulbasher01644/drug-review-dataset-sentiment-analysis/input)
-It consists of drug reviews and their corresponding ratings.
-Sentiment classification is based on the rating values:
  -Positive: Rating ≥ 7
  -Neutral: 4 ≤ Rating < 7
  -Negative: Rating < 4

#DATA PREPROCESSING
-Tokenization and stopword removal using NLTK.
-TF-IDF vectorization for feature extraction.
-Data split into training and test sets.

#IMPLEMENTING THE MODEL
-Logistic Regression model is used for classification.
-GridSearchCV is applied for hyperparameter tuning

#METRICS USED
-Accuracy
-Precision
-Recall
-F1-score
-Confusion Matrix
-Classification Report

