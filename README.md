DATA SCIENCE CHALLENGE SCL WEEK 4
=================================
Predict Card Fraud
==============================  

[![Linkedin: JesusSantana](https://img.shields.io/badge/-JesusSantana-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/chus-santana/)](https://www.linkedin.com/in/chus-santana/) [![GitHub JesusSantana](https://img.shields.io/github/followers/jesussantana?label=follow&style=social)](https://github.com/jesussantana)  

---

![Cardano](https://esmarketingdigital.com/images/card-fraud.png)


## Create a predictive algorithm (Machine Learning, NOT ANN) to predict if a transaction is fraud (class 1) or not (class 2).  

---  

## ✨ BACKGROUND ✨
The datasets contains transactions made by credit cards in September 2013 by european cardholders.  
It contains only numerical input variables which are the result of a PCA transformation.  
Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data.  
Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.  
The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.  
Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.  
The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. 

---  

## ✨ DATASET ✨
- 0 -> Time, numeric variable
- 1-28 -> Predictive numeric features
- 29 -> Amount, numeric variable
- 30 -> Class, this is the target. It is a nominal variable with just 2 unique values (0 and 1)

---

## ✨🏆 TASK 🏆✨
Create a predictive algorithm (Machine Learning, NOT ANN) to predict if a transaction is fraud (class 1) or not (class 2).  

---

## ✨ DELIVERY ✨
Paste the link to your Github repository with two files, one containing all the code you have made in either '.py' or '.ipynb' format.  
And another file with the values predicted by your algorithm, the values that are 0,1 or 2.   
The file with the predictions has to be a '.csv' and only has to be a column with the predictions as it appears in the example file 'example_predictions_delivery.csv'.  

---

Project Organization
--------------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

