# Credit_Risk_Analysis


# Overview of the Project

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.The purpose of this analysis is to create a supervised machine learning model that accurately predict credit risk. We evaluated various machine learning models to determine which is better at predicting credit risk. We used following algorithms/techniques.

Naive Random Oversampling,
SMOTE Oversampling,
Cluster Centroid Undersampling,
SMOTEENN Sampling,
Balanced Random Forest Classifying,
Easy Ensemble Classifying.

** Deliverable 1: Use Resampling Models to Predict Credit Risk
  
 ### Naive Random Oversampling

-Accuracy Score: 66%
-Precision High Risk: 1%
-Precision Low Risk: 100%
-Recall High Risk: 71%
-Recall Low Risk: 61%

![image](https://user-images.githubusercontent.com/92646311/185248825-4eadf30b-c001-48c9-b895-92a171d80541.png)


### SMOTE Oversampling
-Accuracy Score: 66.2%
-Precision High Risk: 1%
-Precision Low Risk: 100%
-Recall High Risk: 63%
-Recall Low Risk: 69%

![image](https://user-images.githubusercontent.com/92646311/185249921-2d02d469-fd0b-4b7d-b851-715c42c20f9d.png)


### Cluster Centroid Undersampling
Accuracy Score: 54.4%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 69%
Recall Low Risk: 4o%

![image](https://user-images.githubusercontent.com/92646311/185250250-681cfcaf-71aa-4f41-b0d5-2408fa4c2ece.png)




Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

### SMOTEENN Sampling
Accuracy Score: 67.4%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 75%
Recall Low Risk: 60%

![image](https://user-images.githubusercontent.com/92646311/185250555-8f5823ed-0487-40f8-bb37-52b82dab8542.png)


Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk 

### Balanced Random Forest Classifying
Accuracy Score: 78.7%
Precision High Risk: 4%
Precision Low Risk: 100%
Recall High Risk: 67%
Recall Low Risk: 91%

![image](https://user-images.githubusercontent.com/92646311/185250765-7939215f-824f-48e4-ad43-fc0c40361f7e.png)


### Easy Ensemble Classifying
Accuracy Score: 92.5%
Precision High Risk: 7%
Precision Low Risk: 100%
Recall High Risk: 91%
Recall Low Risk: 94%

![image](https://user-images.githubusercontent.com/92646311/185250948-50e4989d-d934-459d-a547-660edc5cbe28.png)


# Summary

By Looking at the different models outcome, we can say that the models that perform better is  "Easy Ensemble Classifying with  91% Recall high risk. Also the percision is lower compared to other models. This model would be the first recommendation performing credit risk analusis.





