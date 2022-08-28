# Credit Risk Analysis
Build and evaluate several machine learning algorithms to predict credit risk using Python. <br/> 
To predict credit risk we adopted the following procedure:  <br/>

- Oversample the data using the **RandomOverSampler** and **SMOTE** algorithms.
- Undersample the data using the **ClusterCentroids** algorithm.
- Use a combinatorial approach of over- and undersampling using the **SMOTEENN** algorithm.
- Compare two machine learning models that reduce bias, **BalancedRandomForestClassifier** and **EasyEnsembleClassifier**.

We will evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

### Resources
- Data :&nbsp; [LoanStats_2019Q1.csv](https://drive.google.com/file/d/16AEhrStndfbLWY55DunnV-BdZXBaCuNI/view?usp=sharing)
- Software :&nbsp; [Python](https://www.python.org/downloads/),&nbsp; [Jupyter Notebook](https://www.anaconda.com/products/distribution)

## RandomOverSampler model

![01.png](Images/01.png)

<br/>
he balanced accuracy score is 65%. The high_risk precision is about 1% only with 62% sensitivity which makes a F1 of 2% only.

## SMOTE model

![02.png](Images/02.png)


## ClusterCentroids model

![03.png](Images/03.png)


## SMOTEENN model

![04.png](Images/04.png)


## EasyEnsembleClassifier model

![05.png](Images/05.png)


## BalancedRandomForestClassifier model

![06.png](Images/06.png)
