---
layout: week
title: Week 04
doodle: /doodle.png
---

# XGBoost
## Topics

This week's assignments will guide you through the following topics:

* Understanding the foundational principles behind XGBoost

## Reading

Please read the following:

* Read Section 2c of [An optimized XGBoost based diagnostic system for effective prediction of heart disease](https://www.sciencedirect.com/science/article/pii/S1319157820304936)
* Supplemental reading [XGBoost: A Scalable Tree Boosting System](https://arxiv.org/abs/1603.02754)
* Supplemental reading [XGBoost: Documentation](https://xgboost.readthedocs.io/en/latest/)
* Supplemental reading [An End-to-End Guide to Understand the Math behind XGBoost](https://www.analyticsvidhya.com/blog/2018/09/an-end-to-end-guide-to-understand-the-math-behind-xgboost/)

## Replication task

* Prepare heart data for modeling by:
	* Removing unhelpful variables (e.g., all values coded as missing or all values coded identically)
	* Transforming variables to numeric or categorical based on the data dictionary
	* One-hot encoding categorical variables
	* Converting the resulting dataframe to an array

## Tasks

Complete the following tasks:

* Answer the questions below
* Clean and prepare heart disease dataset to mirror paper


## Weekly Questions

Answer the following questions

* What is training loss and what is regularization? Why do we care about both of these terms in defining an objective function for a supervised learning model?
* What is an ensemble model and specifically how, in general terms, do decision tree ensembles work?
* What is boosting, how is it different than bagging, and why is boosting a useful technique for building models?
* What are 'weak learners'?
