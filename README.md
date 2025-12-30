
# Telcom Churn Analysis using Power BI

Customer Churn is a major challenge for business, particularly in industries with high competition, such as telecommunications, banking and subscription-based services, To address this issue, this project aims to analyze patterns and key factors contributing to Customer attrition and provide actionable insights for business
to enhance their retention strategies.


## Requirements:

## Hardware Requirements:

Processor: Intel i3 or AMD Ryzen 3 or above.

HDD: 500 GB (If SDD is available in your PC it Good for Fast Better File Transfer!).

Ram: 4gb or above (For better Processing!).

Operating System: Windows, Linux or Mac OS (Totally depends on your preference!).

## Software Requirements:

SQL: MS SQL Server.

Tools: MS SQL Server Management Studio (SSMS), Anaconda Navigator (Access Jupyter NoteBook).

Data Visualization: MS Power BI.

Programming Language: Python.

Python Libraires: Matplotlib, Seaborn, Sci-kit, Numpy, Pandas, Joblib.


## Python Libraires Import Packages:

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

import seaborn as sns

from sklearn.model _ selection import train_test_split

from sklearn.ensemble import RandomForestC1assifier

from sklearn.metrics import classification report,confusion_matrix

from sklearn.preprocessing import LabelEncoder

import joblib

##  About the Project:

For companies in many different sectors, customers attrition is a big problem since keeping current ones is usually more affordable than attracting new ones. customers ending their memberships or services causes a churn than results in lost income and higher marketing costs. Business development and sustainability depend on an awareness of the elements causing turnover and a deployment of sensible retention policies. This research seeks to use sophisticated data analysis and machine learning appoaches to build a model for consumers attrition prediction.


## Screenshots

## Dashboard 1: Summary

This Summary Dashboard is been Deployed Which Explains the Overall
Churn Data Which is been Filtered or ETL process is been done from the Raw Datasets. It includes Details such as Gender, Age Group, State, Internet Type, Payment Method, Contract and Its Types, Tenure Group, Churn Category, Services. Identifies Overall Customers, New Joiners, Total Churn and Churn Rate.

![image alt](https://github.com/Siva-17091/My--projects/blob/1fa462442c71f37cc04d31b2329ba7faab18206a/Screenshot%202025-03-17%20153010.png)





## Total Customers:
The Visualization Suite include line Stacked Column charts, Stacked
bar charts cards and slicers for Month-wise Analysis.

![image alt](https://github.com/Siva-17091/My--projects/blob/604c899907f242509f8ebc488e90aa5773a8f70a/Screenshot%201.png)


## Demographics
This, Demographics displays the Total Churn by Gender and Total Customers and Churn Rate by Age Group.

![image alt](https://github.com/Siva-17091/My--projects/blob/5e50d56f145829078559850d7352aeb395ce8923/Screenshot%202.png)

## Geographic
This, Geographic represents the Churn rate by State and Services used are represents Churn Rate by Internet Type.

![image alt](https://github.com/Siva-17091/My--projects/blob/4774e89b2284948067f0f3bb05355f620e98beb1/Screenshot%203.png)

## Account Info

In Account Info, Which represents Churn rate by Payment Method, Total Customers and Churn rate by Tenure Group, Churn rate by Contract.

![image alt](https://github.com/Siva-17091/My--projects/blob/595c87e4be9ba2ee8a33ed6801fd951714ef66f8/Screenshot%204.png)

## Churn Distribution

Illustrates Churn Distribution by Total Churn by Churn Category and Churn by Services.

![image alt](https://github.com/Siva-17091/My--projects/blob/01568350e3cd14e49bee78252ef77f6fb5afff31/Screenshot%205.png)

## Dashboard 2: Churn Reasons

This Churn Reasons is been Created to identify Total Churners and Filtering Each Churn Reasons into a Total Churn.

![image alt](https://github.com/Siva-17091/My--projects/blob/cdb00a3793a4b8cd82b2e3c0dddc3add55a40578/Screenshot%202025-03-17%20212950.png)

## Dashboard 3: Prediction

Prediction Dashboard is been deployed by implementing Random Forest
Algorithm into the Prod_churn table by using Python and Its Libraries with a help of Jupyter Notebook.

![image alt](https://github.com/Siva-17091/My--projects/blob/126925aeb7b1f0761a015e475096fb34fa003bbf/Screenshot%202025-03-17%20213021.png)

## Gender

In this display, Where Churned Customer is been divided into both Male and Female.

![image alt](https://github.com/Siva-17091/My--projects/blob/a95cc814156e3f0fc2743d05e655517893a72603/Screenshot%206.png)

## States

The Churned Customers are been divided According to their States.

![image alt](https://github.com/Siva-17091/My--projects/blob/cbd110724583acf9152e614de3af18a93dd3b70c/Screenshot%207.png)

## Age Group

Also, The Data is been Displayed In Each Age Group Category Which makes to Easier to identify Which Category is been more Churned.

![image alt](https://github.com/Siva-17091/My--projects/blob/0bf58ef4cf18331ba99904eaceab34fce9634902/Screenshot%208.png)

## Marital Status

The Marital Status is been Categorised Wheather, It is Yes or No.

![image alt](https://github.com/Siva-17091/My--projects/blob/b7a9c80bb50dff84dfbbe968921c6f21c9127366/Screenshot%209.png)

## Tenure Group

This, Tenure Group used to Identify in Particular duration of Months The People who have Churned and Payment Methods are using identify Which Type of Payment Method who have Churned.

![image alt](https://github.com/Siva-17091/My--projects/blob/d697f3730b0f05241eeac6f64ace07ebebc07cc3/Screenshot%2010.png)

## Contract

By, Creating Contract We can able to identify No.of.Churned and it is been divided into 3 parts are Months, One year and Two year.

![image alt](https://github.com/Siva-17091/My--projects/blob/89f0e0b3450f4db038f7760fd2984c78bfa621fc/Screenshot%2011.png)
