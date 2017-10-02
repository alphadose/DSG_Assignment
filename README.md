# DSG_Assignment

## Description :-

> An ensemble machine learning model used to predict whether a mushroom is poisonous or not.

## Machine Learning Algorithms used :-

* XGBoost
* Random Forests
* Extra Trees

## Python Libraries used :-

* Pandas
* Numpy
* Scikit-learn

## Brief overview of my approach :-

1. At the beginning I used one hot encoding to create discrete feature columns in the training dataset.

2. After that I chose various bagging and gradient boosting algorithms and compared their performance using cross validation.

3. From those 5 models I picked out 3 on the basis of best accuracy scores.

4. The selected models are then tuned to adapt to the dataset.

5. I created an ensemble from these 3 models in which the final prediction is based on the average of the probabilities with
   which each model predicts the "edible" mushroom class.
 
6. Finally after some preprocessing on the test dataset , the predictions are performed by the model .
  
