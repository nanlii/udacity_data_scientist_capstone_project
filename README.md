# udacity_data_scientist_capstone_project
[**Udacity Data Scientist NanoDegree Program**](https://www.udacity.com/course/data-scientist-nanodegree--nd025)

`Capstone Project - Customer Segmentation Report for Arvato Financial Solutions`
## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Project Motivation](#motivation)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Introduction <a name="introduction"></a>
This is the final capstone project for the [**Udacity Data Scientist NanoDegree Program**](https://www.udacity.com/course/data-scientist-nanodegree--nd025).

Both unsupervised and supervised machine learning techniques are used to analyze attributes and demographic information of the existing clients and compare them with the demographic information of the general population in Germany. The goal is to characterize the customer segment and build a model to predict potential users for the mail-order company.

The project consists of three parts:
1. ETL Process
2. Customer Segmentation Report
3. Supervised Learning Model


## Installation <a name="installation"></a>

1. Mac or Windows System
2. [Anaconda Distribution](https://docs.anaconda.com/free/anaconda/index.html)
3. Libraries: Numpy, Pandas, Matplotlib, Seaborn
4. Packages in the workspace: [Sklearn](https://scikit-learn.org/stable/install.html)

## Project Motivation <a name="motivation"></a>
This is a real-life data science project the datasets are provided by Udacity partners Bertelsmann/Arvato Financial Solutions.The project aims to understand how a mail-order company in Germany can acquire clients more efficiently.

## File Descriptions <a name="files"></a>
```
.
├── Arvato Project Workbook - ETL.html #html version notebook for ETL
├── Arvato Project Workbook - ETL.ipynb #notebook for ETL
├── Arvato Project Workbook - Part1.ipynb #notebook for customer segmentation
├── Arvato Project Workbook - Part2.ipynb #notebook for supervised machine learning model
├── DIAS #attribute dataset
│   ├── DIAS Attributes - Values 2017.xlsx
│   └── DIAS Information Levels - Attributes 2017.xlsx
├── ETL Functions For Part2.ipynb #functions for running customer segmentation part
├── ETL Functions.ipynb #functions for running ETL
├── README.md
├── data
│   ├── Udacity_AZDIAS_052018.csv #demographics data for the general population of Germany
│   ├── Udacity_CUSTOMERS_052018.csv #demographics data for customers of a mail-order company
│   ├── Udacity_MAILOUT_052018_TEST.csv #demographics data for individuals who were targets of a marketing campaign
│   ├── Udacity_MAILOUT_052018_TRAIN.csv #demographics data for individuals who were targets of a marketing campaign
│   ├── ada_best.pickle.dat 
│   ├── azdias_cleaned.csv
│   ├── customers_cleaned.csv
│   ├── gbc_best.pickle.dat
│   ├── mailout_train_cleaned.csv
│   └── xgb_best.pickle.dat
└── terms_and_conditions
    ├── terms.md
    ├── terms.pdf
    └── terms_completed.md
```

## Results<a name="results"></a>

1. By comparing the cluster differences, and understanding the major components in each cluster, I concluded that the customers for the company are most likely to have upper-middle-class cars, live in exclusive neighborhoods with less number of families, and also prefer shopping online.

2. For classification machine learning models, the Ada Boost Classifier had the best result among them all with an ROC Score of 0.79, and the Gradient Boosting Classifier came second with an ROC Score of 0.78, and the XGBoost Classifier was 0.77.

3. The detailed report for this project can be found at the Medium post [here](https://medium.com/@nanlii/customer-segmentation-report-for-arvato-financial-solutions-24cecdf66544).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
This project is part of the Udacity Data Scientist Nano Degree Program, and I'm using the data provided by Bertelsmann/Arvato Financial Solutions.

Thank you :love_you_gesture:
