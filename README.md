March Madness 2018 Predictions.
Use the logistic regression model from scikit-learn package to predict 2018 March Madness games.
Data is from the Google Cloud & NCAA® ML Competition 2018-Men's on kaggle.com (https://www.kaggle.com/c/mens-machine-learning-competition-2018/data).
In the model, I used 12 features to train the model, including the elo rating. The calculation of elo rating is derived from wikipedia:https://en.wikipedia.org/wiki/Elo_rating_system, 
and inspired by paultimothymooney's kernel on kaggle https://www.kaggle.com/paultimothymooney/predict-ncaa-basketball-2017-491782. 
My model achieved a log loss of 0.585 and an accuracy of 71.43% in the 2018 NCAA tournament. 