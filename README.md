# Credit_Risk_Analysis

## Overview of the analysis

## Results: 

Below are screenshots from the balanced accuracy of all the analysis models

-   The ClusterCentroid model proved to be the least accurate at 54%

-   The EasyEnsembleClassifier model proved to be the most accurate at 93%

-   The difference between the most and least accurate was 39 points.

![ClusterCentroids](images/ClusterCentroids_accuracy.png){width="355"}

![SMOTEENN](images/SMOTEENN_accuracy.png){width="355"}

![RandomOverSampler](images/RandomOverSampler_accuracy.png){width="355"}

![SMOTE](images/SMOTE_accuracy.png){width="355"}

![BalancedRandomForestClassifier](images/BalancedRandomForestClassifier_accuracy.png){width="355"}

![EasyEnsembleClassifier](images/EasyEnsembleClassifier_Accuracy.png){width="355"}

-   The balance accuracy scores were solidified by the precision and recall scores. Below we can see that while the average of the precision is the same, the recall scores are very different. The first image is from the EasyEnsembleClassifier model while the bottom image is the ClusterCentroid model.

    ![EasyEnsembleClassifier_pre_rec](images/EasyEnsembleClassifier_pre_rec.png){width="436"}

    ![](images/ClusterCentroids_pre_rec.png){width="425"}

## Summary: 

Based on the analysis conducted using the six models, the EasyEnsembleClassifier model has the highest balance accuracy score as well as the best recall at of all models. I would recommend the EasyEnsembleClassifier model of analysis for future modeling. Working with these models highlights the importance of trying different methods until you achieve consistent informative results.
