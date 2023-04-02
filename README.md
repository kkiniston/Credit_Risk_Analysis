# Credit_Risk_Analysis

## Background
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.
- 1: Use Resampling Models to Predict Credit Risk
- 2: Use the SMOTEENN Algorithm to Predict Credit Risk
- 3: Use Ensemble Classifiers to Predict Credit Risk
- 4: A Written Report on the Credit Risk Analysis (README.md)

## Summary and Analysis of Results
![Screenshot 2023-04-02 014031](https://user-images.githubusercontent.com/115853964/229339467-e8f314a0-57dc-4eab-b7b4-4d2f15784c31.png)

### Undersampling 
![Screenshot 2023-04-02 014446](https://user-images.githubusercontent.com/115853964/229339646-e15bff0b-e816-4f66-9391-935784d39756.png)

The accuracy score resulted in[0.5443043836656818] **545% score**


### SMOTE 
![Screenshot 2023-04-02 014403](https://user-images.githubusercontent.com/115853964/229339605-75fc774a-e6c9-4bba-b93b-e89c27bab5aa.png)

The accuracy score resulted in[0.662394124702461] **66% score**

### Oversampling 
![Screenshot 2023-04-02 014310](https://user-images.githubusercontent.com/115853964/229339574-969f237b-a3c3-472d-b180-e95afdd9884b.png)

The accuracy score resulted in[0.646602844334948] **66% score**

### Combination 
![Screenshot 2023-04-02 014547](https://user-images.githubusercontent.com/115853964/229339679-a62b5fa6-7622-473f-9cde-837c17bc7dee.png)

The accuracy score resulted in[0.6400726134353378] **64% score**



