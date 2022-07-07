
# Duplicate-Question-Pairs

A binary classification problem,for a given pair of questions we need to predict whether the are duplicate or not.

Dataset link:https://www.kaggle.com/competitions/quora-question-pairs/data
# Heroku link:
https://my-duplicate-question-pairs.herokuapp.com/
# Bussiness Constraint:
The cost of miscalssification can be very high because imagine that I have two questions which are not duplicates of each other but if I declare them to be duplicate then all the answers of question 1 will be referred as answers to question 2 which can be extremely dangerous.Users can easily figure out if answers are not relevant to question 2, they will be disappointed and the trust on the platform as an ecosystem of great answers will be lost.
Used bag of words because it lead to least classfications


Model used:RandomForestClassifier
