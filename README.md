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


- SMOTE model 
![image](https://user-images.githubusercontent.com/85530690/136484568-d860b92e-fa6d-4b5d-8db6-8901f4f3f660.png)

![image](https://user-images.githubusercontent.com/85530690/136484608-8ac1cfca-52d6-4abc-b187-8a6eba867495.png)

![image](https://user-images.githubusercontent.com/85530690/136484644-b4369d22-0db9-4cda-bea0-c162d0accc85.png)


- ClusterCentroids model 
![image](https://user-images.githubusercontent.com/85530690/136484709-ac6a6210-69cb-4b83-aedb-598bc6e00cdd.png)

![image](https://user-images.githubusercontent.com/85530690/136484759-243e42b3-5eb2-4d33-824c-2ee76ebb0378.png)

![image](https://user-images.githubusercontent.com/85530690/136484795-0456d708-857e-4af8-a397-b66d468181d5.png)

- SMOTEENN model

- BalancedRandomForestClassifier model

- EasyEnsembleClassifier model


## Summary:

- There is a summary of the results 

- There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
