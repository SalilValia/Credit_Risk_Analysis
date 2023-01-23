# Credit_Risk_Analysis
 Module 18 

## Analysis overview
For this challenge we use Python to create and analyze several machine learning models to predit the credit risk from the data. We oversampled the data using RandomOverSampler and SMOTE method. For undersample, we used the ClusterCentroids method. For a combination approach for over and under sampling we used the SMOTEENN method. Then finally we used the BalancedRandomForestClassifier and the EasyEnsembleClassifier to compare the two and reduce doubts. 

## Results
For RandomOverSampler 



![image](https://user-images.githubusercontent.com/111409181/213948501-6c62b0a9-89f0-4f7f-9ff6-fce30a89f758.png)

The balanced accuracy score is 64%.
The high_risk precision is about 1% only with 61% sensitivity makes the F1 of 2% only.
With the high number of the low_risk population, its precision is 100% with a sensitivity of 67%.

For the SMOTE model

![image](https://user-images.githubusercontent.com/111409181/213950247-d63ed349-6261-41f5-af94-a6cca63bcb85.png)

The results were pretty similar to the RandomOverSampler model
The balanced accuracy score is 63%.
The high_risk precision is about 1% only with 60% sensitivity makes the F1 of 2% only.
With the high number of the low_risk population, its precision is 100% with a sensitivity of 66%.

For the ClusterCentroids model

![image](https://user-images.githubusercontent.com/111409181/213950959-e0c2a2fb-a147-4fc2-93d2-feb292696445.png)


The balanced accuracy score is 63%.
The high_risk precision is about 1% only with 61% sensitivity makes the F1 of 1% only.
With the high number of the low_risk population, its precision is 100% with a sensitivity of 45%.

For the SMOTEENN model

![image](https://user-images.githubusercontent.com/111409181/213951465-ce79c9b5-4d54-4a3b-a214-30cda19f251a.png)


The balanced accuracy score is 64%.
The high_risk precision is about 1% only with 69% sensitivity makes the F1 of 2% only.
With the high number of the low_risk population, its precision is 100% with a sensitivity of 60%.






