# Credit_Risk_Analysis
 Module 18 

## Analysis overview
For this challenge we use Python to create and analyze several machine learning models to predit the credit risk from the data. We oversampled the data using RandomOverSampler and SMOTE method. For undersample, we used the ClusterCentroids method. For a combination approach for over and under sampling we used the SMOTEENN method. Then finally we used the BalancedRandomForestClassifier and the EasyEnsembleClassifier to compare the two and reduce doubts. 

## Results
For RandomOverSampler 



![image](https://user-images.githubusercontent.com/111409181/213948501-6c62b0a9-89f0-4f7f-9ff6-fce30a89f758.png)

The balanced accuracy score is 64%.
The high_risk precision is about 1% only with 61% sensitivity makes the F1 of 2% only.
With the high number of the low_risk population, its precision is almost 100% with a sensitivity of 67%.

For the SMOTE model

![image](https://user-images.githubusercontent.com/111409181/213950247-d63ed349-6261-41f5-af94-a6cca63bcb85.png)

The balanced accuracy score is 63%.
The high_risk precision is about 1% only with 60% sensitivity makes the F1 of 2% only.
With the high number of the low_risk population, its precision is almost 100% with a sensitivity of 66%.


