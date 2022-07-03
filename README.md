# Credit_Risk_Analysis

## Overview of the Analysis

### Purpose

The purpose of this challenge is to assess various machine learning models and determine which model is best suited to determine Credit Risk,
based on Accuracy,Precision and Recall(sensitivity).

## Results

### RandomOverSampler:

![image](https://user-images.githubusercontent.com/99941484/177053071-56d93d84-c8fc-4729-9b3e-bea0d62127bc.png)

* Accuracy - 64%
* Precision - 99%
* Recall - 60%


### SMOTE Oversampling:

![image](https://user-images.githubusercontent.com/99941484/177053088-a2342e92-23a9-4260-af7e-0bcfa9d32215.png)

* Accuracy - 66%
* Precision - 99%
* Recall - 69%


### Undersampling:

![image](https://user-images.githubusercontent.com/99941484/177053127-22d68587-05f4-4657-aace-a28e859d5a39.png)

* Accuracy - 52%
* Precision - 99%
* Recall - 40%


### SMOTEENN:

![image](https://user-images.githubusercontent.com/99941484/177053145-caf6926a-3726-44c9-920d-472fce123898.png)

* Accuracy - 64%
* Precision - 99%
* Recall - 58%


### BalancedRandonForestClassifier

![image](https://user-images.githubusercontent.com/99941484/177053208-f298b2f1-8d8b-4696-8c6e-9daddba646d4.png)

* Accuracy - 78%
* Precision - 99%
* Recall - 87%


### EasyEnsembleClassifier

![image](https://user-images.githubusercontent.com/99941484/177053223-227f6b84-bfbb-4d3e-9170-927dc2152100.png)

* Accuracy - 93%
* Precision - 99%
* Recall - 94%


## Summary 

* Accuracy - When comparing all 6 ML models only Easy Ensemble Classifier shows an accuracy of 93 percent.

* Precision- All the models show a precision rate of 99 Percent

* Recall - From the above results we can conclude that the best recall rate is for Easy Ensemble Classifier at 94 Percent.

## Recommendation

For predicting Credit Risk it is important to look at the recall rate and from the above results we were able to conclude that the best recall rate is for Easy Ensemble Classifier Model. So, it is recommended we use Easy Ensemble Classifier model for predicting Credit Risk.
