##  Semi-conductor Manufacturing Process Test Result Classification 

- Binary Classification, Feature Selection

### Project Overview

- The Purpose of this project is to **classify the binary test result** of semiconductor manufacturing process, 'Fail' or 'Pass' which represent the true yield in the house line testing.
  
- Supervised Machine Learning Algos including Logistic Regression, Support Vector Classifier, Random Forest Classifier, and XGBoost Classifer are applied.
  
- Dataset is UCI ML repo SECOM data, with data description below.

### Data Description 
- Data Source:
  - McCann, M. & Johnston, A. (2008). SECOM [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C54305.
- Kaggle Link: https://www.kaggle.com/datasets/paresh2047/uci-semcom/data
- Data Set Characteristics: Multivariate
- Number of Instances: 1567
- Number of Attributes: 591
- Missing Value: Yes

### Repo Structure

```
- data/ : Store the raw data from kaggle
- figures/ : Contain all figures genertaed from the whole project
- results/ : Contain trained model results under 5 different random states
- report/ : Contain the project report including intro, EDA, Methodology, Result, Outlook, and References 
- src/ :Include source codes,
  - EDA
  - Model Development, which have the whole ML pipeline, trained the model and output the best resultss;
  - Model Evluation, which evluate the model performance, inspect the model, analyze feature importance and other related evaluation
```

#### Enviornment Requirement: 

A few key packages in this project:

```
* pickleshare=0.7.5
* scikit-learn=1.5.1
* numpy=1.26.4
* pandas=2.2.2
* scipy=1.14
* scipy 1.9.1
* seaborn==0.13.2
* shap=0.45.1
* py-xgboost=2.1.1
```

The enviornment is created via conda. You can also use environment.yml as complete configuration and package dependencies refeerence. 
