# Workers_Retention

![](EmployeeRetention.jpg)


## Problem Definition 
The goal is to predict with machine learning the likelihood of employee turnover or employee retention in the company and what can be done to help reduce the likelihood of employee turnover. 

---
## File Guide

HR_data.csv :  The Human Resource dataset for this project. 

Predicting _workers_retention.ipynb : Jupyter notebook for the project. 

## Features Engineering Process:

Here I went in-depth to do features engineering before building my models  

## EDA: Exploratory Data Analysis: 

An extensive Exploratory Data Analysis was carried out to get the best features for my modelling 

## Modelling Technique: 

Models were built using three different modelling techniques such as: 

Logistic Regression 

Random Forest 

Gradient boosting with Cross Fold Validation set to 5 

# Insights

There are 3 distinct clusters for employees who left the company

**Cluster 1** (Hard-working and Sad Employee): Satisfaction was below 0.2, and evaluations were greater than 0.75. This could indicate that employees who left the company were good workers but felt horrible at their jobs.

*Question: What could be the reason for feeling so horrible when highly evaluated? Could it be working too hard? Could this cluster mean employees who are "overworked"?*

**Cluster 2** (Bad and Sad Employee): Satisfaction between about 0.35~0.45 and evaluations below ~0.58. This could be seen as badly evaluated employees who felt bad at work.

*Question: Could this cluster mean employees who "under-performed"?*


**Cluster 3** (Hard-working and Happy Employee): Satisfaction between 0.7~1.0 and evaluations were greater than 0.8. Which could mean that employees in this cluster were "ideal". They loved their work and were evaluated highly for their performance.

Also, I got an insight into random forest features importance to see the important features that help make my predictions
and found:

**Workers Satisfaction**, 

**Years working in the company** as features that help predict if there will be worker turnover or not

Check the **.ipynb** file to see more.

Great work!

