# Credit_Risk_Analysis

# Overview

The purpose of this analysis is to gain insights into Lending Club's credit risk dataset through the use of Machine Learning. To compensate for the inherent classification problem of credit risk, it is important to use a variety of techniques to evaluate and predict credit risk. 

6 Machine Learning algorithms are utilized to analyze data in the following ways:

## Oversampling of data:
1. RandomOverSampler and 
2. SMOTE

## Undersampling of data:
3. ClusterCentroids


## Combinatorial approach of over and under sampling:
4. SMOTEENN

## Models to reduce bias:
5. BalancedRandomForestClassifier
6. EasyEnsembleClassifier


# Results

## Deliverable 1: Use Resampling Models to Predict Credit Risk

### RandomOverSampler model

 - The balanced accuracy score is 67%

![RandomOverSampler Balanced Accuracy](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/ros_ba_score.png)

 - The high risk precision rate is 1% with the recall at 74% giving this model an F1 of 2%. The low risk precision rate is 100% with a recall at 61%
 
![RandomOverSampler Confusion Matrix](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/ros_confusion_matrix.png)

![RandomOverSampler Precision & Recall](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/ros_prec_recall_score.png)

### SMOTE model

 - The balanced accuracy score is 66%

![SMOTE Balanced Accuracy](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/smote_ba_score.png)

 - The high risk precision rate is 1% with the recall at 63% giving this model an F1 of 2%. The low risk precision rate is 100% with a recall at 69%

![SMOTE Precision & Recall](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/smote_prec_recall_score.png)


### ClusterCentroids Model

 - The balanced accuracy score is 54%

![ClusterCentroids Balanced Accuracy](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/clcent_ba_score.png)


 - The high risk precision rate is 1% with the recall at 69% giving this model an F1 of 1%. The low risk precision rate is 100% with a recall at 40%

![ClusterCentroids Precision & Recall](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/clcent_precf_recall_score.png)



Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk

### SMOTEENN model

 - The balanced accuracy score is 64%

![SMOTEENN Balanced Accuracy](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/smoteenn_ba_score.png)


 - The high risk precision rate is 1% with the recall at 72% giving this model an F1 of 2%. The low risk precision rate is 100% with a recall at 57%

![SMOTEENN Precision & Recall](https://github.com/RebeccaA79/Credit_Risk_Analysis/blob/main/images/smoteenn_prec_recall_score.png)

Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk

### BalancedRandomForestClassifier model

 - The balanced accuracy score is

 - The high risk precision rate is 1% with the recall at  giving this model an F1 of %. The low risk precision rate is 100% with a recall at %

### EasyEnsembleClassifier model

 - The balanced accuracy score is

 - The high risk precision rate is 1% with the recall at  giving this model an F1 of %. The low risk precision rate is 100% with a recall at %

# Summary
