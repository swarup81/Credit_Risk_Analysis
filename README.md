# Credit_Risk_Analysis

# Overview of the analysis

## Purpose:

In this challenge, we apply machine learning to solve a real-world challenge: credit card risk. Credit risk is an unbalanced classification problem, as good loans easily outnumber risky loans. 
This project aims to train and evaluate models with unbalanced classes.

# Results: 

* Naive Random Oversampling

The balanced accuracy score is 64%.
The high_risk precision is about 1%, with a sensitivity of 70%.
The low-risk precision is 100% with 59% of sensitivity.

* SMOTE Oversampling

The balanced accuracy score is 66%.
The high_risk precision is about 1%, with a sensitivity of 63%.
The low-risk precision is 100% with 69% of sensitivity.

* Cluster Centroid Undersampling

The balanced accuracy score is 54%.
The high_risk precision is about 1%, with a sensitivity of 69%.
The low-risk precision is 100% with 40% of sensitivity.

* SMOTEENN 

The balanced accuracy score is 65%.
The high_risk precision is about 1%, with a sensitivity of 73%.
The low-risk precision is 100% with 57% of sensitivity.

* BalancedRandomForestClassifier model

The balanced accuracy score is 78%.
The high_risk precision is about 3%, with a sensitivity of 70%.
The low-risk precision is 100% with 87% of sensitivity.

* EasyEnsembleClassifier model

The balanced accuracy score is 93%.
The high_risk precision is about 9%, with a sensitivity of 92%.
The low-risk precision is 100% with 94% of sensitivity.

# Summary:

In credit risk analysis, all the models show low precision in determining high credit risk with high sensitivity.
Based on the analysis, I recommend  Easy Ensemble AdaBoost Classifier model because it has a 0.93 balanced accuracy score. The balanced accuracy score of 0.93 gives us a better idea of how well the model can predict both classes.
