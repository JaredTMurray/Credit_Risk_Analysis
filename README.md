# Credit_Risk_Analysis
##	Overview of the analysis: 
 I have used the credit card credit dataset from LendingClub, a peer-to-peer lending services company, 
 - I have used the oversampling method for the data by using the RandomOverSampler and SMOTE algorithms, as well as used the undersampling method for the data by using the ClusterCentroids algorithm. 
 - The combination approach of oversampling and undersampling using the SMOTEENN algorithm were used for Delivable #2. 
 - For Delivable #3, I compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 
 
Please note that I did ran into some programming errors, however I continued to work towards the end with the code that I have learnt in this module.

## Results: 
####	Deliverable 1: Use Resampling Models to Predict Credit Risk.
 - I have used the Binary encoding with Pandas (multiple columns) to remove the string values and replace it with numeric values. It created the feature and target values that I used in the loan_status colunm. See file [credit_risk)resampling](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb). 
 - The split train and test values had a Counter of ({1: 51366, 0: 246})
 
  ![](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/Oversample.png)

####	Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
-  I have used teh undersampling method in the file [credit_risk)resampling](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb)
![](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/Undersample.png)
- Combination of Over and under sample methos was used to find confusion matrix 
![](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/Over_Under.png)

####	Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.
The Ensemble classifier with balancedrandon methed was used in [credit_risk_ensemble](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/credit_risk_ensemble.ipynb)

![](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/ensemble.png)
##	Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

