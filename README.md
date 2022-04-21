# Credit_Risk_Analysis

## Overview
* In this analyis I was tasked to predict whether somebody is a low or high risk for a loan based off of a CSV with a ton of different factors. The libraries used to create our model were the imbalanced-learn and scikit-learn and then to use a resampling method to help evalute them. I used two approaches to this task, one of them I oversampled data with randommoversample and smote algorithms and undersampled data using the clustercentroid algorithm. The second approach was for me to over and undersample using smoteenn. Afterwards, I used machine learning models to help minimize bias.

## Results: 
* Naive Random Oversampling: The accuracy of the balance test is 66%, precision for high risk is 1% and at the same time, 72% recall. 
![image](https://user-images.githubusercontent.com/95777297/164363277-c9a322d2-9a90-4609-a8ab-c0635ab9568c.png)
* SMOTE oversampling: Accuracy for this test is 64%, the precision the high risk is 1% with 72% recall. 
![image](https://user-images.githubusercontent.com/95777297/164363734-b1483051-df15-4085-8706-e260302de28d.png)
* 
