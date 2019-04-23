# house-prices

Predict sales prices and practice feature engineering.

#### About

This is from a Kaggle competition.

<https://www.kaggle.com/c/house-prices-advanced-regression-techniques/>

#### Data

Unzip the .zip file. The only files you need are `train.csv` and `data_description.txt`. Do not use the `test.csv` as it is only useful for the Kaggle competition.

You will not be submitting results to Kaggle. This is only for in-class work.

#### Instructions

Fork and Clone this repository.

You are trying to predict the **Sale Price** of a house based on various predictors.

This is a regression, so after preparing the the data (eda, splits, feature engineering, etc.), do a **linear regression** first using the `sklearn` implementation. What is the **MSE** on the *test set*, not on *training*.

Next, build a neural network. You are free to try as many architectures as you'd like, also try various optimizers, and other miscellaneous hyperparameters.

Plot the **MSE** for both training and validation as a function of epochs.

Once again, what is the **MSE** of this model on the *test set*.

Which model performed the best?

