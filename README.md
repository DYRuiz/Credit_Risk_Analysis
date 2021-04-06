# Credit Risk Analysis

## Overview

This analysis is to compare the effectiveness of various supervised machine learning models in determining credit risk.  The data used is a credit card credit dataset from LendingClub, a peer-to-peer lending services company.  The models used for sampling were:
- Native Random Oversampling
- SMOTE Oversampling
- Cluster Centroid Sampling
- SMOTEEN samping
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

## Results

#### Native Random Oversampling
Balanced Accurary Score: 0.6603423204808787

![ClassificationReport](images/NativeRandomOversampling.png)

#### SMOTE
Balanced Accuracy Score: 0.6537310478007576

![ClassificationReport](images/SMOTE.png)

#### Cluster Centroids
Balanced Accruary Score: 0.5447339051023905

![ClassficationReport](images/ClusterCentroids.png)

#### SMOTEEN
Balanced Accuracy Score: 0.6447993752836463

![ClassificationReport](images/SMOTEEN.png

#### Balanced Random Forest Classifier
Balanced Accuracy Score: 0.7885466545953005

![ClassficationReport](images/BalancedRandomForest.png)

#### Easy Ensemble AdaBoost Classifier
Balanced Accuracy Score: 0.9316600714093861

![ClassificationReport](images/EnsembleAdaBoost.png)


## Summary
Of the models used, the Easy Ensemble AdaBoost Classifier had the highest metrics overall and for both individual classes (high risk / low risk).  Based on this analysis, this model is recommended to predict credit risk.  The other models did well with the low-risk classification but not as well with the high risk which is the primary objective.  
