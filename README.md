# Credit_Risk_Analysis

## Overview of the analysis: 
A peer-to-peer lending services company wants to use machine learning to predict credit risk. The hope is that this will provide a quicker and more reliable loan experience. The theory is that machine learning will lead to a more accurate identification of good candidates for loans, which will lead to lower default rates. I have used six different machine learning models, and describing the outcome of each. 

## Results: 
Included here is a summary of each of the machine learning models that have been analalized. For each of the models, the balanced accuracy score, and the precision and recall scores will be dicsussed. 

* RandomOverSampler (Naive Random Oversampling)
   * Balanced Accuracy Score = 0.66
   * Precision = 0.99
   * Recall = 0.62
* SMOTE Oversampling 
   *   Balanced Accuracy Score = 0.66
   *   Precision = 0.99
   *   Recall = 0.69
* ClusterCentroids Undersampling
   *   Balanced Accuracy Score = 0.54
   *   Precision = 0.99
   *   Recall = 0.40
* SMOTEENN Undersampling
   *   Balanced Accuracy Score = 0.64
   *   Precision = 0.99
   *   Recall = 0.57
* BalancedRandomForestClassifier
   *   Balanced Accuracy Score = 0.79
   *   Precision = 0.99
   *   Recall = 0.87
* EasyEnsembleClassifier
   *   Balanced Accuracy Score = 0.79
   *   Precision = 0.99
   *   Recall = 0.87

## Summary: 
To make it easier to interpret, I have put the six machine learning models and their scores in a table. I have also put in there my top recommendations on the top of the table, then moving down the teable to my least recommendated machine learning model to the right side. 

|   |Precision | Accuracy   | Recall  |
|---|---|---|---|
|BalancedRandomForestClassifier   |0.99|0.79| 0.87|
|EasyEnsembleClassifier           |0.99|0.79|0.87|
|SMOTE                            |0.99|0.66|0.69|
|   RandomOverSampler             |0.99|0.66|0.62|
|SMOTEENN                         |0.99|0.64|0.57|
|ClusterCentroids                 |0.99|0.54|0.40|

In summary, every one of the six machine learning models that were ran had the same precision score or 99%, so that isn't a deicding factor when chosing what machine learning model to use. However, my top suggestions would be to use either the BalancedRandomForestClassifier or the EasyEnsembleClassifier as though had the highest balanced accuarcy socres, both at 79%, and the highest recall values, both at 87%. 
