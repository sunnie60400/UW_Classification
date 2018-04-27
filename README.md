# UW_Classification

W1: Predicting Sentiment from Product Reviews (Text Mining)
- Perform data cleaning (texting cleaning)
- Use sklearn.feature_extraction.text.CountVectorizer to convert a collection of texts to a matrix of token counts
- Use sklearn.linear_model.LogisticRegression to train logistic regression models to predict the sentiment of product reviews
- Inspect the coefficients of the logistic regression models and interpret their meanings
- Make predictions (both class and probability) of sentiment for a new product review
- Compare multiple logistic regression models by computing their accuracy

W2(I): Implementing Logistic Regression
- Implement the link function for logistic regression
- Write a function to compute the derivative of the log likelihood function with respect to a single coefficient
- Implement gradient ascent
- Make predictions of sentiment given a set of coefficients
- Compute classification accuracy for the logistic regression model

W2(II): Logistic Regression with L2 Regularization
- Write a function to compute the derivative of log likelihood function with an L2 penalty with respect to a single coefficient
- Implement gradient ascent with an L2 penalty.
- Empirically explore how the L2 penalty can ameliorate overfitting

W3(I): Identifying Safe Loans with Decision Trees
- Turn categorical variables into binary features via one-hot encoding
- Use sklearn.tree.DecisionTreeClassifier to train decision tree models using different max_depth
- Use predict(), prdict_prob() to make predictions
- Use score() to assess to performance of decision tree models
- Compute number of false negative and false positive
