# MiniProject_02

This project uses the following datset, which can be downloaded from Kaggle: https://www.kaggle.com/datasets/mirichoi0218/insurance
This project does three things:

1. Full EDA with plenty of visualization
2. Seven models to predict 'charges', and comparison of these models
3. Flagging characterization of 'expensive' customers

The project shows that the main correlations in the data are smoking vs charges and age vs charges. These visual plots are very evident of these findings.
The seven models that are run are a Simple Linear Regression, Multivariable Linear Regression, Polynomial Regression, Ridge Regression, Lasso Regression, Support Vector Regression, and Decision Tree Regression.
Of the models run, the most effective predictor was a Polynomial Regression of degree 2, to avoid overfitting the data. 
Lastly, this model has great Classification scores: 

Accuracy: 0.933

Precision: 0.960

Recall: 0.903

Full analysis of the visuals and models, as well as an in-depth analysis of the accuracy metrics is written in the PDF. It is suggested to clear the Colab session and rerun all of the cells to ensure the code runs cleanly.
