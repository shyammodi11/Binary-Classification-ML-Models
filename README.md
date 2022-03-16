# Binary-Classification-ML-Models

## [CREDIT CARD FRAUD DETECTION](https://github.com/shyammodi11/Binary-Classification-ML-Models/blob/main/CREDIT_CARD.ipynb)

Understanding the Problem

•	For financial banks around the world, identifying credit card fraud is crucial. Banks have to spot potential fraud so that their costumers don't pay for goods they haven't purchased. This is important so that the customer doesn't lose money and the bank does not lose its customers.

•	Hence, the ultimate goal is to tackle this situation by building generalized classification models which tracks the pattern of all the transactions to classify and distinguish fraud transactions from the normal ones.

•	This is a binary classification problem.

### About the Dataset

•	The dataset consists of 31 feature columns and 284807 rows. Due to security issues, 28 of the features are the result of the PCA transformation. 'Time' and 'Amount are the only columns that were not modified with PCA. The output variable is named 'Class'.

•	There are no null/missing values in this dataset. All feature columns are float64 or int64 values. The output variable is heavily imbalanced.

![image](https://user-images.githubusercontent.com/72390323/158182076-f61eb290-e300-49cb-bbbd-54cdb26244e8.png)

### Fraudulent transactions distribution

![image](https://user-images.githubusercontent.com/72390323/158184030-ce2697f4-f395-4ff6-8963-4fb0e07d3d3b.png)

 
### Train-Test Split

Dividing data and sampling training/testing set to balance the output variable.
 
![image](https://user-images.githubusercontent.com/72390323/158572758-907dc451-c280-4e81-b62e-aa1e77e1d480.png)


Algorithms Used For Classification
1.	Logistic Regression
2.	Decision Tree
3.	Random Forest 
4.	Ensembling techniques – Stacking, Boosting
5.	Naïve Bayes
6.	KNN

### Top performing models
1.	AdaBoost

![image](https://user-images.githubusercontent.com/72390323/158572278-3dee11b7-8889-4590-bf1f-86f1e2636db6.png)

![image](https://user-images.githubusercontent.com/72390323/158572347-f9e096f2-c5c2-4d11-babd-5fe289fa7c3b.png)

2.	Gradient Boosting

![image](https://user-images.githubusercontent.com/72390323/158572443-30f544b4-b1a8-4bbe-b50b-53c282c6f297.png)

3. Random Forest

![image](https://user-images.githubusercontent.com/72390323/158571637-4214e817-d59a-4450-8b40-456e70826ca6.png)

![image](https://user-images.githubusercontent.com/72390323/158572000-bd8cb0e0-1997-4060-8a62-59a1d7dc02e5.png)

### Summary

•	Accuracy of ADABoost model is: 0.9320345102452291

•	Recall value : 0.9035612134852534

•	F1 score: 0.93

•	Accuracy of Gradient Boosting model is: 0.93

•	Recall value: 0.86

•	F1 score: 0.92

•	Stacking and Random forest algorithms also performed well after some hyper-parameter tuning.

### Conclusion

•	In this machine learning project, a binary classifier was implemented using various classification algorithms to predict potential fraud transactions. Through this project, several techniques were applied to address feature selection, check correlation and treat major class imbalance problem.

•	28 features columns out of 31 are the result of the PCA transformation. The output variable is named 'Class'. Visualizing data distribution with respect to time and frequency was necessary. However, the dataset was heavily imbalanced. Only 0.17% of all transactions were fraudulent.

### Results

•	Looking at model results, the best accuracy on the test set was achieved by the boosting technique algorithms followed by Logistic Regression. Boosting is an ensemble meta-algorithm that converts weak learners to strong ones. Important features were showcased while using Decision tree and Random Forest.

