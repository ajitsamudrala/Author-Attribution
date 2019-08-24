Authorship Attribution
=========================

The dataset has articles and their corresponding authors. The tesk is to find a decision function that maps article to an author. The dataset has 50 authors. Hence, it is a multiclass classification.

One of the intresting things I tried was to combine outputs of Bidirectional LSTM based deep learning model with TF-IDF vectors and train an XGboost model on the combined matrix. Though it was the not the best model. 

Models Trained
=====

* Naive Bayes
* Multinomial Naive Bayes
* Logistic Regression OVR
* XGBoost
* XGBoost on Combined Matrix



