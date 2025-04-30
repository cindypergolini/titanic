This repository contains a possible solution for the Kaggle Competition "Titanic, Machine Learning from disaster".
The goal is to submit a model to forecast if one passenger would survive based on the features provived by the data.
I am a newbie, so I don't guarantee for the exactness of my approach.
I chose to proceed in this way:
-First exploratory data analysis: analyzing missing data and fill it by imputation, see correlation maps and plot variables on against the others to see which feature influence the result the most
-Engineering features
-Finally choose a model: I chose to train RandomForest model using SciKit-Learn because it's easy to use, it can deal with non linear data and can handle rumorous datasets
