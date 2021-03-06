# Credit Risk Analysis
## Overview
In this report we look at credit card data and use different types of machine learning algorithms to help us find the best accuracy for high risk loans. 

## Results 
Results are ordered from worst to best performing

UnderSampling 
* 51.9% Accuracy Score
* 1% Precision 
* 59% Recall
[RandomOverSampling](Photos/undersampling.PNG)

SMOTE OverSampling 
* 63.5% Accuracy Score
* 1% Precision 
* 62% Recall
![](Photos/smoteoversampling.PNG)

Random OverSampling 
* 64.7% Accuracy Score
* 1% Precision 
* 63% Recall
![](Photos/oversampling.PNG)
 
Random OverSampling 
* 65% Accuracy Score
* 1% Precision 
* 72% Recall
![](Photos/overundersampling.PNG)

Random Forest 
* 79.5% Accuracy Score
* .8% Precision 
* 91% Recall
![](Photos/randomforest.PNG)

AdaBoost
* 92.6% Accuracy Score
* .8% Precision 
* 92% Recall
![](Photos/adaboost.PNG)

## Summary
Looking at the models we can see that AdaBoost clearly performed better than all other classifiers used. It had an outstanding 92.6% accuracy rate and 92% recall rate. Both highest out of all models. In fact AdaBoost was more than 12% higher than the next closest individual. For this reason I would recommend using AdaBoost as the best model for detecting high risk loans. 
