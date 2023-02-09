# SUTD-Hate-Speech-Machine-Learning-Competition

The SUTD Machine Learning Competition focused on training a machine learning model to detect hate speech given a large dataset of text. There is a traning set, which the model will be trained on, and a testing set, which the model will be tested on. 

The final model that the team agreed on was a combination of Naive Bayes, XGBoost and Logistic Regression. In order to tune the model, we tune the hyperparameter using grid search. We use wandb to help us to log the macro F1-score and select the hyperparameter that has the highest average f1 score across the 10 folds. Wandb is an experiment tracking tool for machine learning 
