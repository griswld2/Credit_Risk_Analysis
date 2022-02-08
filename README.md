# Credit_Risk_Analysis

## Overview:
The purpose of the analysis was to determine the best predictive model to leverage to determine which consumers had a high risk and a low risk of defaulting on loans based off of historical customer data. 
## Results:
![alt text](https://github.com/griswld2/Credit_Risk_Analysis/blob/main/images/naive_sampling.PNG)
* Naive Random Sampling Results:
    * Accuracy: 51%
    * High Risk Precision: 100%
    * High Risk Sensitivity: 1%
![alt text](https://github.com/griswld2/Credit_Risk_Analysis/blob/main/images/smote_sampling.PNG)
* Smote Oversampling Results:
    * Accuracy: 68%
    * High Risk Precision: 1%
    * High Risk Sensitivity: 67%
![alt text](https://github.com/griswld2/Credit_Risk_Analysis/blob/main/images/undersampling.PNG)
* Undersampling (ClusterCentroid) Results:
    * Accuracy: 68%
    * High Risk Precision: 1%
    * High Risk Sensitivity: 60%
 ![alt text](https://github.com/griswld2/Credit_Risk_Analysis/blob/main/images/combo_Sampling.PNG)
* Combination (Over and Under) Sampling Results:
    * Accuracy: 52%
    * High Risk Precision: 1%
    * High Risk Sensitivity: 70%
![alt text](https://github.com/griswld2/Credit_Risk_Analysis/blob/main/images/balanced_forest.PNG)
* Balanced Random Forest Results:
    * Accuracy: 80.2%
    * High Risk Precision: 4%
    * High Risk Sensitivity: 69%
![alt text](https://github.com/griswld2/Credit_Risk_Analysis/blob/main/images/eec_sampling.PNG)
* Easy Ensemble Results:
    * Accuracy: 92.5%
    * High Risk Precision: 7% 
    * High Risk Sensitivity: 91%
 
## Summary:
Based off of the results of the different predictive models, I would recommend using the <b>Easy Ensemble ML Model</b>. This model has the highest level of accuracy and also has a high risk sensitivity. Although there are downfalls of not having a high precision by turning down applicants who aren't at high risk of defaulting on credit, it makes more sense to be conservative with who we are giving out lines of credit to and giving out loans in order to ensure that we are protecting our own company and our customer's ability to pay back their loans. The high sensitivity means that we will be turning down people who are true positives and false positives for high risk, which means we are protecting ourselves against credit defaults.  
