# Credit_Risk_Analysis

## Overview of the Analysis/Purpose
The purpose of this project is to analyze a LendingClub credit card credit dataset using various machine learning models, and evaluate the performance of these models in order to recommend whether they should be used to predict credit risk.  Models utilized during the analysis are Naive Random Oversampling, SMOTE Ovesampling, Undersampling, SMOTEENN, Balanced Random Forest Classifier and Easy Ensemble Classifier.  Tools utilized for this analysis include Jupyter Notebook, Pandas, Numpy and the imbalanced-learn and scikit-learn libraries.  

## Results
### Balanced Accuracy Scores
Balanced accuracy scores showed a wide range of variation between models, from a low of 0.55 with the undersampling model to a high of 0.93 with the Easy Ensemble AdaBoost Classifier. 

- Naive Random Oversampling

![Screen Shot 2022-04-27 at 8 24 06 PM](https://user-images.githubusercontent.com/90944163/165657715-a85dc744-7f4f-4c82-8a52-d5c61efa779c.png)

- SMOTE Oversampling

![Screen Shot 2022-04-27 at 8 25 33 PM](https://user-images.githubusercontent.com/90944163/165657822-9a4e5cfa-c113-422b-9d2b-e2d7c43c0c4f.png)

- Undersampling 

![Screen Shot 2022-04-27 at 8 26 30 PM](https://user-images.githubusercontent.com/90944163/165657913-a1c48512-21cc-4c14-bc8c-9eff89c068fd.png)

- SMOTEENN

![Screen Shot 2022-04-27 at 8 27 48 PM](https://user-images.githubusercontent.com/90944163/165658024-11e547f7-44f9-4801-8806-0db1c5712478.png)

- Balanced Random Forest Classifier

![Screen Shot 2022-04-27 at 8 29 12 PM](https://user-images.githubusercontent.com/90944163/165658169-dc036109-f9b1-4fea-853b-40914e7e0f15.png)

- Easy Ensemble AdaBoost Classifier

![Screen Shot 2022-04-27 at 8 30 47 PM](https://user-images.githubusercontent.com/90944163/165658316-196ff442-6d67-4fce-aabb-d4e27097858a.png)

### Precision And Recall Scores
Precision scores amongst the 6 models were all very similar, as shown below, ranging from 0.01 to 0.09 for high risk and 0.99 for low risk. Recall scores showed much greater variation, ranging from 0.49 to 0.92 for high risk and 0.55 to 0.94 for low risk.  

- Naive Random Oversampling

![Screen Shot 2022-04-27 at 8 38 41 PM](https://user-images.githubusercontent.com/90944163/165659027-fbb9b392-381a-4c14-9d91-187155c9f5f6.png)

- SMOTE Oversampling

![Screen Shot 2022-04-27 at 8 38 14 PM](https://user-images.githubusercontent.com/90944163/165658992-f0a6d6b7-b9be-4f1c-babf-13ad6bef70ff.png)

- Undersampling 

![Screen Shot 2022-04-27 at 8 37 39 PM](https://user-images.githubusercontent.com/90944163/165658941-fcb548fd-7363-4bc1-b948-5c9ea7e9cbbc.png)

- SMOTEENN

![Screen Shot 2022-04-27 at 8 37 07 PM](https://user-images.githubusercontent.com/90944163/165658894-8b7d9364-9d92-452b-8378-325c8b512ef0.png)

- Balanced Random Forest Classifier

![Screen Shot 2022-04-27 at 8 36 36 PM](https://user-images.githubusercontent.com/90944163/165658849-cef3d5ea-1880-42f8-bb66-4537c15c666d.png)

- Easy Ensemble AdaBoost Classifier 

![Screen Shot 2022-04-27 at 8 35 54 PM](https://user-images.githubusercontent.com/90944163/165658784-ad601674-abf9-438b-a349-6bc93d6b6588.png)

## Summary

