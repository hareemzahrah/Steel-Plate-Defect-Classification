# Steel-Plate-Defect-Classification
BS semester machine learning project for classifying steel plate surface defects using Logistic Regression, Random Forest, and XGBoost.

There are 1941 plates, 27 features, and 7 types of defect

Models Used
Logistic Regression
Random Forest
XGBoost

Cross validation is done with 5-fold stratified cross validation to evaluate the models.

Results

XGBoost
Accuracy: 81.1% ± 1.2%
Macro F1: 83.1% ± 1.3%

Random Forest
Accuracy: 78.3% ± 0.5%
Macro F1: 80.3% ± 1.0%

Logistic Regression
Accuracy: 66.4% ± 1.5%
Macro F1: 66.3% ± 1.3%

The highest accuracy and macro F1-score was achieved by XGBoost with an average accuracy of 81.1% and macro F1-score of 83.1%.

Dataset Classes
The project divides plates into 7 types of fault:

Pastry
Z_Scratch
K_Scratch
Stains
Dirtiness
Bumps
Other_Faults


Project Goal:
The primary goal is to compare the performance of different classic machine learning between them and determine the best model to classify the defects of steel plates
