# Customer segmentation and customer prediction for Arvato Financial Solutions

The project is the capstone for the Udacity Machine Learning Engineer Nanodegree. 


## Project

In the project we analyzed demographics data for customers of a mail-order sales company in Germany, comparing it against demographics information for the general population. We performed customer segmentation using a clustering technique, identifying the parts of the population that best describe the core customer base of the company. We then used different supervised learning models to predict which individuals are most likely to convert into becoming customers for the company.


## Data 

The data provided for the project was the following:

1. `azdias.csv` - Demographics data for the general population of Germany - 891,211 persons (rows) x 366 features (columns)

2. `customers.csv` - Demographics data for customers of a mail-order company - 191,652 persons (rows) x 369 features (columns)

3. `mailout_train.csv` - Demographics data for individuals who were targets of a marketing campaign (train) - 42,982 persons (rows) x 367 (columns)

4. `mailout_test.csv` - Demographics data for individuals who were targets of a marketing campaign (test) - 42,833 persons (rows) x 366 (columns)

5. `DIAS Information Levels - Attributes 2017.xlsx` - Description of the features

6. `DIAS Attributes - Values 2017.xlsx` - Description of the features and their values


## Libraries
The code uses python 3 and requires the following packages: numpy, pandas, matplotlib, seaborn, sklearn, lightgbm, catboost, h2o, shap.


## Kaggle
The supervised learning portion of the project was part of a Kaggle competition. On July 4 2020 we ranked 11th out of 215 participants.
