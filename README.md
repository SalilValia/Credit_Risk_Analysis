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

For the BalancedRandomForestClassifier model

![image](https://user-images.githubusercontent.com/111409181/213952712-e2b53ccf-2f26-4573-9ab0-4fe137e93174.png)


The balanced accuracy score is 79%.
The high_risk precision is about 4% only with 67% sensitivity makes the F1 of 7% only.
With the high number of the low_risk population, its precision is 100% with a sensitivity of 91%.

For the EasyEnsembleClassifier model

![image](https://user-images.githubusercontent.com/111409181/213955345-07a7fb52-efbc-4fb4-b763-4d263ba6fcb8.png)


The balanced accuracy score is 93%.
The high_risk precision is about 7% only with 91% sensitivity makes the F1 of 14% only.
With the high number of the low_risk population, its precision is 100% with a sensitivity of 94%.

## Summary 
Overall the data does not seem to useful in predicting if a credit card applicant is high risk. The models we used to perform the credit risk analysis show weak precision in determining if a credit risk is high. The EasyEnsembleClassifier model shows a recall of 91% so it will notify us of it being a high risk credit. Although, with a low precision, a lot of low risk credits are still noticeable as high risk which would penalize the bank's credit strategy and effect on their revenue by not taking those business opportunities. Therefore, I would suggest the bank to not use any of these models to predict credit risk.
