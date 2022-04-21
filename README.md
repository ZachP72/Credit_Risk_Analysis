# Credit_Risk_Analysis

## Overview
* In this analyis I was tasked to predict whether somebody is a low or high risk for a loan based off of a CSV with a ton of different factors. The libraries used to create our model were the imbalanced-learn and scikit-learn and then to use a resampling method to help evalute them. I used two approaches to this task, one of them I oversampled data with randommoversample and smote algorithms and undersampled data using the clustercentroid algorithm. The second approach was for me to over and undersample using smoteenn. Afterwards, I used machine learning models to help minimize bias.

## Results: 
* Naive Random Oversampling: The accuracy of the balance test is 66%, precision for high risk is 1% and at the same time, 72% recall. 
![image](https://user-images.githubusercontent.com/95777297/164363277-c9a322d2-9a90-4609-a8ab-c0635ab9568c.png)
* SMOTE oversampling: Accuracy for this test is 64%, the precision the high risk is 1% with 72% recall. 
![image](https://user-images.githubusercontent.com/95777297/164363734-b1483051-df15-4085-8706-e260302de28d.png)
* Undersampling: 65.6% accuracy, 99% precision, and recall of 40%. 
![image](https://user-images.githubusercontent.com/95777297/164363915-68aa3856-985c-4d63-9727-4935546749a0.png)
* Combination: Accuracy of 64%, 99% precision, and 57% recall. 
![image](https://user-images.githubusercontent.com/95777297/164364013-11139bc8-68ba-4bf3-8be5-43e09c4e60d7.png)
* Balanced Random Forest Classifier: Accuracy of 77%, 99% precision, and 88% recall.
![image](https://user-images.githubusercontent.com/95777297/164364316-38b060a4-6bbb-413b-8583-fdac7f669fd9.png)
* Easy Ensemble AdaBoost Classifier: Accuracy has a score of 91.8% with 99% precision and recall of 94%.
![image](https://user-images.githubusercontent.com/95777297/164364415-91026dd3-e7ec-4290-a01c-9e0b12edcb52.png)

## Summary: 
* Out of the models that I created I recommend the easy ensemble classifiers. The easy ensemble was the most balanced of the models due to its high accuracy score and good balance of precision and recall scores. The rest of the tests resulted in low accuracy scores which tends to be problematic. 
