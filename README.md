# Credit_Risk_Analysis

The following deliverables included in this analysis:

 - Deliverable 1: Use Resampling Models to Predict Credit Risk
 - Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk
 - Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk
 - Deliverable 4: A Written Report on the Credit Risk Analysis 

## Overview of the loan prediction risk analysis:

- The purpose of this analysis is to apply machine learning to solve a real-world challenge: credit card risk.  Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans.  In this analysis I have employed different techniques to train and evaluate models with unbalanced classes. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once done, evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results:

- RandomOverSampler model

![image](https://user-images.githubusercontent.com/85530690/136484039-82101300-06bb-4435-932f-ed1026cfff9c.png)


![image](https://user-images.githubusercontent.com/85530690/136484312-c712f7ba-4761-4f0b-9929-dd1e58269920.png)

![image](https://user-images.githubusercontent.com/85530690/136484453-463bff5d-131f-4a50-a8cb-08a17e755ce4.png)

The balanced accuracy score is:  64%.
The high_risk precision is approximately 1%, 


- SMOTE model 

- ClusterCentroids model 

- SMOTEENN model

- BalancedRandomForestClassifier model

- EasyEnsembleClassifier model


## Summary:

- There is a summary of the results 

- There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
