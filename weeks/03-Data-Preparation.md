---
layout: week
title: Week 03
doodle: /doodle.png
---

# Data Preparation

## Topics

This week's assignments will guide you through the following topics:

* Understanding the authors' motivations for constructing an XGBoost classifier, and why they think it's a suitable approach to the problem they present
* Preparing data for XGBoost classifier construction, including handling of categorical features through one-hot encoding and converting the response variable to a binary representation

## Reading

Please read the following:

* Read Sections 1, 2.1, 2.2, 2.6, and 3.1 of [An optimized XGBoost based diagnostic system for effective prediction of heart disease](https://www.sciencedirect.com/science/article/pii/S1319157820304936)
* Supplemental reading [Data Preparation for Gradient Boosting with XGBoost in Python](https://machinelearningmastery.com/data-preparation-gradient-boosting-xgboost-python/)
* Supplemental Reading [Data Cleaning with Python](https://medium.com/bitgrit-data-science-publication/data-cleaning-with-python-f6bc3da64e45)
* Useful documentation for considering model pipeline [Scikit-Learn Decision Tree](https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html)

## Replication task

* Read in the heart dataset ([HeartData_Full.csv](../data/HeartData_Full.csv)) and explore the variable types
* One-hot encode the categorical variables
* Convert the response variable (num) into a binary variable in the same way the authors do
* Create a pipeline for determining if there are "problem" features with non-numeric values, missing data, etc
* Use pipeline to look at any correlations / obvious relationships between pairwise features


## Tasks

Complete the following tasks:

* Complete the required reading and answer the questions below.
* Complete the replication tasks above, referring to the supplemental reading if necessary. 


## Weekly Questions

Answer the following questions

* In your own words, describe what the authors are doing in this paper? What's their motivation and what's their goal?
* Where does the dataset that the authors use (and that you'll use) come from? How was the data collected and what information is included?
* What is one-hot encoding and why is necessary in this case?
* What other data manipulations do the authors apply and why do they do them?
