# Kaggle-Titanic competition Machine Learning - Classification Models

## Problem Description

This EDA is for beginning with Kaggle competition and implementing some most widely used binary classifiers.

The sinking of the RMS Titanic is one of the most infamous shipwrecks in history. On April 15, 1912, during her maiden voyage, the Titanic sank after colliding with an iceberg, killing 1502 out of 2224 passengers and crew. This sensational tragedy shocked the international community and led to better safety regulations for ships.

One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class.

## Objective

In this challenge, we will complete the analysis of what sorts of people were likely to survive. In particular, we will apply the tools of machine learning to predict which passengers survived the tragedy.

## Methodology

* Created Title column from Name column. Created Family size by combining Parch and SibSp
* Filled missing values using Median(transform() method)- For Age column
* Classification Models used – KNN classifiers, Decision tree classifier, ADABoost, Random forest classifier,  Support vector classifier, XGBoost classifier, Ensemble modelling.
* Prediction score of - 0.7889- 4600 out of 21000
 

## Code and Resources Used

    Python Version: 3.7
    Packages: pandas, numpy, sklearn, matplotlib, .
