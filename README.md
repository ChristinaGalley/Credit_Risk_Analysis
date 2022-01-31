# **Credit_Risk_Analysis**
---
## Overview
---
The purpose of this analysis is to compare and determine the best machine learning model for predicting credit risk. Imbalanced-learn and scikit-learn libraries were used to build and evaluate models using resampling. Different techniques were employed to train and evaluate models with unbalanced classes. The credit card credit dataset from LendingClub was oversampled using the RandomOverSampler and SMOTE algorithms, and undersampled using the ClusterCentroids algorithm. A combinatorial approach of over- and undersampling using the SMOTEENN algorithm was completed. Lastly, the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier were used to predict credit risk.
---
## Results
---
**Native Random Oversampling**
-Balanced accuracy score:
![picture alt]()

- High Risk Loans: Precision = 1%, recall score = 71%
- Low Risk Loans: Precision = 100%, recall score = 60%
- Average/total: Precision = 99%, recall score = 60% 
![picture alt]()

**Smote Oversampling**
-Balanced accuracy score:
![picture alt]()

- High Risk Loans: Precision = 1%, recall score = 63%
- Low Risk Loans: Precision = 100%, recall score = 69%
- Average/total: Precision = 99%, recall score = 69% 
![picture alt]()

**ClusterCentroids Undersampling**
-Balanced accuracy score:
![picture alt]()

- High Risk Loans: Precision = 1%, recall score = 69%
- Low Risk Loans: Precision = 100%, recall score = 40%
- Average/total: Precision = 99%, recall score = 40% 
![picture alt]()

**SMOTEENN Combination Sampling**
-Balanced accuracy score:
![picture alt]()

- High Risk Loans: Precision = 1%, recall score = 72%
- Low Risk Loans: Precision = 100%, recall score = 57%
- Average/total: Precision = 99%, recall score = 57% 
![picture alt]()

**Balanced Random Forest Classifier**
-Balanced accuracy score:
![picture alt]()

- High Risk Loans: Precision = 3%, recall score = 70%
- Low Risk Loans: Precision = 100%, recall score = 87%
- Average/total: Precision = 99%, recall score = 87% 
![picture alt]()

**Easy Ensemble AdaBoost Classifier**
-Balanced accuracy score:
![picture alt]()

- High Risk Loans: Precision = 9%, recall score = 92%
- Low Risk Loans: Precision = 100%, recall score = 94%
- Average/total: Precision = 99%, recall score = 94% 
![picture alt]()

---
## Summary
Based on these results, the Easy Ensemble AdaBoost Classifier seems to be the best overall model for precicting credit risk with an accuracy of 93%, average precision of 99%, and average recall of 94%. The other tested models have accuracy scores that all fall under 80% as well as lower precision and recall scores. Out of the 6 models, I would recommend using the Easy Ensemble AdaBoost Classifier model to predict credit risk.
