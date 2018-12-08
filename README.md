# alexa-reviews-dataset
Implementing Naive Bayes algorithm to predict the review: if the review is positive or negative.
I took Amazon Alexa reviews dataset from Kaggle and preprocessed the data. Then I used Bag Of Words(BOW) vectorizer after splitting the data into train and test datasets and implemented BOW on train data. Then I've encorporated Naive Bayes algorithm by choosing the best Alpha value from Grid Search CV and performed it on test data to predict the rating of a review from test dataset. After fetching the values, I've checked for accuracy which is found to be 94%.
