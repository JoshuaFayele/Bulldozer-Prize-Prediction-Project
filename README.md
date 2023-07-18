# Bulldozer-Prize-Prediction-Project
This notebook looks into using various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting the sale price of bulldozers.

The following approach will be used:
1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Definition

In a statement,
> How well can we predict the future sale price of a bulldozer, given its characteristics and previous examples of how much similar bulldozers ave been sold for?

## 2. Data

The data is downloaded from the Kaggle Bluebook for Bulldozers competition:
https://www.kaggle.com/competitions/bluebook-for-bulldozers/data

There are 3 main datasets:
* Train.csv: The training set, which contains data through the end of 2011.
* Valid.csv: The validation set, which contains data from January 1, 2012 to April 30, 2012.
* Testt.csv: The test set, which contains data from May 1, 2012 to November 2012


## 3. Evaluation

> The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more on the evaluation of this project, check:
https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview/evaluation

**Note:** The goal of this project is to build a machine learning model which minimises RMSLE.


## 4. Features

You can view the data dictionary provided by Kaggle using this google sheets:
https://docs.google.com/spreadsheets/d/1_bZNYiG1hmSkqGkIkzaKLo1Ef6zBJ7C_/edit#gid=982566454
