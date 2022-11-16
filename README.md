# Credit_Risk_Analysis

## Overview of the analysis: 
A peer-to-peer lending services company wants to use machine learning to predict credit risk. The hope is that this will provide a quicker and more reliable loan experience. The theory is that machine learning will lead to a more accurate identification of good candidates for loans, which will lead to lower default rates. I have used six different machine learning models, and describing the outcome of each. 

## Results: 
Included here is a summary of each of the machine learning models that have been analalized. For each of the models, the balanced accuracy score, and the precision and recall scores will be dicsussed. 

* RandomOverSampler (Naive Random Oversampling)
   * Balanced Accuracy Score = 0.66
   * Precision = 0.99
   * Recall = 0.69
* SMOTE Oversampling 
   *   Balanced Accuracy Score = 0.66
   *   Precision = 0.99
   *   Recall = 0.69
* ClusterCentroids Undersampling
   *   Balanced Accuracy Score = 0.54
   *   Precision = 0.99
   *   Recall = 0.40
* SMOTEENN (Combination Over and Under) Sampling
   *   Balanced Accuracy Score = 0.64
   *   Precision = 0.99
   *   Recall = 0.57
* BalancedRandomForestClassifier
   *   Balanced Accuracy Score = 0.78
   *   Precision = 0.99
   *   Recall = 0.87
* EasyEnsembleClassifier
   *   Balanced Accuracy Score = 0.78
   *   Precision = 0.99
   *   Recall = 0.87

## Summary: 
In summary, every one of the six machine learning models that were ran had the same precision score or 99%, so that isn't a deicding factor when chosing what machine learning model to use. In practice, I would suggest to use either the BalancedRandomForestClassifier or the EasyEnsembleClassifier as though had the highest balanced accuarcy socres, both at 78%, and the highest recall values, both at 87%. 
