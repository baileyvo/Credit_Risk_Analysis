# Credit_Risk_Analysis

## Overview
### Purpose
The purpose of this analysis was to evaluate the performance of various models (imbalanced-learn and scikit-learn libraries) to understand the performance of the models and to make a recommendation of whether they should be used to predict credit risk.

## Results
The balanced accuracy score and the precision and recall scores of all six machines where analyzed. The results were as follows:

### Naive Random Oversampling
![Naive Random Oversampling](https://github.com/baileyvo/Credit_Risk_Analysis/blob/main/Images/naive_random_oversampling.PNG)

- Balanced Accuracy: 0.6249984891886339
- Precision: High-risk loans: low, Low-risk loans: high
- Recall: High/Low risk = 0.60/0.65

### SMOTE Oversampling
![SMOTE Oversampling](https://github.com/baileyvo/Credit_Risk_Analysis/blob/main/Images/SMOTE_oversampling.PNG)

- Balanced Accuracy: 0.6512584051472337
- Precision: High-risk loans: low, Low-risk loans: high
- Recall: High/Low risk = 0.64/0.66

### Undersampling
![Undersampling](https://github.com/baileyvo/Credit_Risk_Analysis/blob/main/Images/undersampling.PNG)

- Balanced Accuracy: 0.6512584051472337
- Precision: High-risk loans: low, Low-risk loans: high
- Recall: High/Low risk = 0.64/0.66

### Combination Under-Over Sampling
![Combination Under-Over Sampling](https://github.com/baileyvo/Credit_Risk_Analysis/blob/main/Images/combination.PNG)

- Balanced Accuracy: 0.6375241226214794
- Precision: High-risk loans: low, Low-risk loans: high
- Recall: High/Low risk = 0.70/0.57

### Balanced Random Forest Classifier
![Balanced Random Forest Classifier](https://github.com/baileyvo/Credit_Risk_Analysis/blob/main/Images/balanced_random_forest_classifier.PNG)

- Balanced Accuracy: 0.7877672625306695
- Precision: High-risk loans: low, Low-risk loans: high
- Recall: High/Low risk = 0.67/0.91

### Easy Ensemble AdaBoost Classifier
![Easy Ensemble AdaBoost Classifier](https://github.com/baileyvo/Credit_Risk_Analysis/blob/main/Images/easy_ensemble.PNG)

- Balanced Accuracy: 0.925427358175101
- Precision: High-risk loans: low, Low-risk loans: high
- Recall: High/Low risk = 0.91/0.94

## Summary
For this data set, the **Easy Ensemble AdaBoost Classifier** is the best model, as it has the highest balanced accuracy of the six models at aroun 93%, with all other models showing a balanced accuracy of under 80%. Precision was similar for all models. The Easy Ensemble AdaBoost Classifier had the highest recall score though, so it would be the best model to choose for further analysis of this type. 

