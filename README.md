# Credit_Risk_Analysis
Build and evaluate several machine learning algorithms to predict credit risk using Python. <br/> 
To predict credit risk we adopted the following procedure:  <br/>

- Oversample the data using the **RandomOverSampler** and **SMOTE** algorithms.
- Undersample the data using the **ClusterCentroids** algorithm.
- Use a combinatorial approach of over- and undersampling using the **SMOTEENN** algorithm.
- Compare two machine learning models that reduce bias, **BalancedRandomForestClassifier** and **EasyEnsembleClassifier**.
