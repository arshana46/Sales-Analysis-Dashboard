# Sales-Analysis-Dashboard

A beginner-friendly Superstore Sales Analysis project with data cleaning, visualization, logistic regression, and an interactive Excel dashboard.

This project explores the Superstore dataset by performing a full data analytics workflow — from data cleaning and exploratory analysis to machine learning modeling and dashboard creation. The goal of this project is to understand sales patterns, identify key insights, and build a simple model to predict whether an order is profitable.


---

### Project Overview

This project covers:

### Data Cleaning

Removed duplicates

Handled missing values

Cleaned column formats

Prepared dataset for analysis and modeling

Saved the cleaned dataset for dashboard creation


### Exploratory Data Analysis (EDA)

Using Python (Pandas, Matplotlib), I analyzed patterns across:

Category-wise Sales

Sub-Category Sales

Region-wise Sales

Segment-wise Sales

Overall sales performance trends


### Visualizations include:

Bar Charts

Pie Charts

Simple comparison plots


These visual insights helped understand which products and regions drive the highest sales.


---

### Machine Learning Model

I created a simple classification model based on features like:

Sales

Quantity

Discount

Region

Category

Segment

Ship Mode


### Target Variable

A new column was created:

ProfitFlag = 1 if Profit > 0 else 0

This allowed the model to predict whether an order is Profitable (1) or Not Profitable (0).

### Steps

Encoded categorical features (one-hot encoding)

Split dataset using train_test_split

Trained a Logistic Regression model

Evaluated using:

Accuracy Score

Confusion Matrix

True vs Predicted comparison table



This gave a simple, beginner-friendly ML pipeline.


---

### Excel Dashboard

After saving the cleaned dataset, I designed an interactive dashboard in Excel using:

Pivot Tables

Pivot Charts

Category, Region, Segment-based views




The dashboard gives a quick, professional overview of:

Sales performance

Category-wise contribution

Region-wise distribution

Overall business insights



---

### Skills Demonstrated

Data Cleaning

Exploratory Data Analysis

Feature Encoding

Logistic Regression

Train-Test Split

Confusion Matrix Evaluation

Excel Pivot Tables

Excel Dashboard Design

Data Storytelling
