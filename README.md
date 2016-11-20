#Titanic Competition - Kaggle

## Context
Here is my code for the Titanic Competition on Kaggle.

I try different classifiers, and the one that got the me best ranking on the public leaderboard is a Random Forest whose parameters have been found via a Grid Search

## Requirements

To run this code, you need to have :

* pandas
* numpy
* Scikit-learn
* XGBoost


## Running instructions

Simply run the jupyter notebook, the prediction will be outputed in titanic.csv

## Code structure
1. Import the data
2. Data visualization
3. Feature engineering
4. Training (gridsearchCV)
5. Testing (K fold validation)