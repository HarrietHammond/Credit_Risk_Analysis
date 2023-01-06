# Credit_Risk_Analysis

## Overview 

### This project seeks to employ different techniques to train and evaluate models with unbalanced classes. Imbalanced-learn and scikit-learn libraries will be used to build and evaluate the models using resampling. Utilizing a credit dataset provided from LendingClub, a peer-to-peer lending services company, the data will be oversampled using RandomOverSampler and SMOTE algorithms. It will be undersampled using the ClusterCentroids algorithm. Then, a combinatorial approach of over, and under sampling using the SMOTEEN algorithm. Also, a comparison of two new machine learning models that reduce bias and to predict credit risk will be deployed.
### Finally, a performance evaluation of these models will be established, and a written recommendation on whether they should be used to predict credit risk.


## Results

### Deliverables 1, 2 and 3 - Balanced accuracy scores, precision scores and recall scores. 
### Predicting Credit Risks using SMOTEEN, SMOTE, RandomOverSample, ClusterCentroids, EasyEssembleClassifier and BalancedRandomForestClassifier.

#### ![image](https://user-images.githubusercontent.com/112135658/210933886-8dd1227f-c8a1-4a0e-9cd0-9f51faa12ec6.png)



#### ![image](https://user-images.githubusercontent.com/112135658/210933964-86810751-dd9d-483e-a7f1-4828734f98bd.png)


#### ![image](https://user-images.githubusercontent.com/112135658/210934035-e7c93b51-a88a-47f5-8d66-7bcc1a2d699d.png)


#### ![image](https://user-images.githubusercontent.com/112135658/210934117-a7d284c6-fd64-4f19-afaa-5e67a2861675.png)


#### ![image](https://user-images.githubusercontent.com/112135658/210934161-81842390-3d80-4990-85f7-3c05e9d4ac6e.png)



#### ![image](https://user-images.githubusercontent.com/112135658/210934211-453ae6ba-6d3f-464d-8f7f-88b52bff8a6f.png)



## Summary

#### All the models had low precisions, so they were quite comparable in obtaining the desired results of predicting credit risks as shown in the results above.
#### EasyEnsembleClassifier was the most effective model amongst all the models utilized. It offered a highest score for all Risk loans. 

#### The recommendation will be to use the EasyEnsembleClassifier model as it provided the Highest-Risk loan precision amongst all the models employed.

