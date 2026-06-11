# Restaurant-Sentiment-Analysis
"Sentiment analysis of restaurant reviews using NLP and Naive Bayes."
# Restaurant Review Sentiment Analysis

This project performs sentiment analysis on restaurant reviews using NLP 
(text cleaning, stopword removal, stemming) and a Bag of Words model with 
a Multinomial Naive Bayes classifier.

## Dataset
Restaurant_Reviews.tsv — 1000 labeled reviews (1 = positive, 0 = negative)

## Steps
1. Text preprocessing (cleaning, stemming, stopword removal)
2. Feature extraction using CountVectorizer (Bag of Words)
3. Train/test split (80/20)
4. Model training with Multinomial Naive Bayes
5. Hyperparameter tuning (alpha)
6. Evaluation using accuracy, precision, recall, confusion matrix
7. Custom sentence prediction

## How to run
Open the notebook in Google Colab and run cells in order. Make sure 
Restaurant_Reviews.tsv is in the same folder or update the path accordingly.
