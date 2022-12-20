# Review-Helpfulness-Identification
The aim of this project is to create a model that can identify the online customer reviews as helpful or not helpful and to check how do features like length of review, review score and sentiment of the reviews can be used to identify reviews as helpful or not helpful.
In this project different classification algorithms (Support Vector Machine, Gaussian Naive Bayes, AdaBoost, Random Forest, Logistic Regression and Decision Tree) are evaluated on Flipkart dataset to predict the helpfulness of reviews.
Feature space is expanded by adding review length, review score, sentiment and polarity scores of all the reviews. Sentiment and Length of reviews were scaled from 0 to 1 and were combined with TF-IDF in training different models.
A function is created that could be used to train and evaluate five different classification algorithms (Support Vector Machine, Gaussian Naive Bayes, AdaBoost, Random Forest, and Logistic Regression) on the review dataset with different sizes of 2500, 5000 and 9403.
# Analysis
Different classification algorithms are trianed and  performance of each classification algorithm is evluated on the three different sizes of datasets. This process involved measuring the time taken by each algorithm to train and predict labels, generating classification reports and calculating the ROC and AUC scores.
The performance of the different models are compared and it is identified that the SVC algorithm had the highest scores for the used  data.
