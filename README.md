## Logistic Regression for tweets sentiment analysis

Imagine you’re building a sentiment analysis system that can automatically detect whether a tweet expresses a positive or negative emotion. To do this, you’ll train a logistic regression model that learns from thousands of labeled tweets.

 - Steps for building a logistic regression classifier:

 - Clean and preprocess each tweet using tokenization, stopword removal, and stemming

 - Extract key features based on the frequency of positive and negative words

 - Implement the logistic (sigmoid) function to map predictions to probabilities between 0 and 1

 - Compute the cost function and apply gradient descent to learn model weights

 - Use the trained model to predict sentiment on unseen tweets and evaluate accuracy

### Results:
After training, your logistic regression classifier achieves about 99.5% accuracy on the test set, correctly identifying the sentiment of most tweets. You also perform error analysis to understand which types of tweets are still misclassified.
