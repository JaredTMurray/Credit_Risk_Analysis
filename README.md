# Credit_Risk_Analysis
##	Overview of the analysis: 
 I have used the credit card credit dataset from LendingClub, a peer-to-peer lending services company, 
 - I ahve used oversample the data by using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. 
 - The combinatorial approach of over- and undersampling using the SMOTEENN algorithm were used for Delivable #2. 
 - For Delivable #3, I compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 
 
Please note that I did ran into some programming errors, however I continued to work towards the end with the code I have learnt in this module.

## Results: 
####	Deliverable 1: Use Resampling Models to Predict Credit Risk.
 - I have used the Binary encoding using Pandas (multiple columns) to remove the string values and replace it with numberic values. to create the feature and taget values I used yj loan_status colunm. See file [credit_risk)resampling](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb) 
  ![](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/Oversample.png)

####	Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
-  I have used teh undersampling method in the file [credit_risk)resampling](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/credit_risk_resampling.ipynb)
![](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/Undersample.png)
- Combination of Over and under sample methos was used to find confusion matrix 
![](https://github.com/JaredTMurray/Credit_Risk_Analysis/blob/main/Over_Under.png)

####	Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.
The Ensemble classifier with balancedrandon methed was used in 
![]()
##	Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

