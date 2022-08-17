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

-Accuracy Score: 67.4%
-Precision High Risk: 1%
-Precision Low Risk: 100%
-Recall High Risk: 72%
-Recall Low Risk: 63%

![image](https://user-images.githubusercontent.com/92646311/185248825-4eadf30b-c001-48c9-b895-92a171d80541.png)


### SMOTE Oversampling
Accuracy Score: 66.2%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 66%
Recall Low Risk: 66%

### Cluster Centroid Undersampling
Accuracy Score: 51.3%
Precision High Risk: 0%
Precision Low Risk: 100%
Recall High Risk: 61%
Recall Low Risk: 42%



Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk

### SMOTEENN Sampling
Accuracy Score: 68.1%
Precision High Risk: 1%
Precision Low Risk: 100%
Recall High Risk: 76%
Recall Low Risk: 60%

Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk 

### Balanced Random Forest Classifying
Accuracy Score: 64.8%
Precision High Risk: 56%
Precision Low Risk: 100%
Recall High Risk: 30%
Recall Low Risk: 100%

### Easy Ensemble Classifying
Accuracy Score: 92.3%
Precision High Risk: 6%
Precision Low Risk: 100%
Recall High Risk: 91%
Recall Low Risk: 94%

# Summary
. Looking through the different models, the ones that scored the highest were:

Easy Ensemble Classifying (91%)
SMOTEENN Sampling (76%)
Naive Random Oversampling (72%)


another important statistic is recall rate for low risk as it shows how many low risk loans are flagged as high risk.

Balanced Random Forest Classifying (100%)
Easy Ensemble Classifying (94%)


After taking these two statistics over the others, we can look at the accurary score to get a picture of how well the model performs in general. The models with the highest accuracy scores were:

Easy Ensemble Classify (92.3%)
SMOTEENN Sampling (68.1%)
Balanced Random Forest Classifying (64.8%)
After factoring in these three main statistics, the model that I would recommend to use for predicting high risk loans is the Easy Ensemble Classifying model.
