# Olist E-Commerce Analytics & Customer Intelligence Project

## Project Overview

This project presents an end-to-end business analytics study of the Olist Brazilian E-Commerce Marketplace.

The objective was to analyze marketplace performance, customer behavior, operational efficiency, revenue growth, customer retention, and future business opportunities using statistical analysis, forecasting, customer segmentation, and machine learning.

The project covers the complete analytics lifecycle:

* Data Cleaning & Feature Engineering
* Business KPI Analysis
* Statistical Experimentation
* Bayesian Inference
* Bootstrap Analysis
* CUPED Variance Reduction
* Sequential Testing
* Monte Carlo Forecasting
* Customer Segmentation (RFM)
* Customer Retention Prediction

---

## Dataset Summary

| Metric                |  Value |
| --------------------- | -----: |
| Orders                | 98,666 |
| Customers             | 95,420 |
| Sellers               |  3,095 |
| Revenue               |  20.3M |
| Average Order Value   | 205.83 |
| Average Review Score  |   4.03 |
| On-Time Delivery Rate | 90.09% |

---

## Key Business Findings

### 1. Strong Acquisition, Weak Retention

Customer acquisition performance is strong, but retention remains the largest growth challenge.

* Average customer frequency = 1.03 orders
* Approximately 97% of customers purchased only once

This indicates substantial opportunity to increase customer lifetime value through retention-focused initiatives.

---

### 2. Delivery Performance Drives Satisfaction

Customer satisfaction is strongly influenced by delivery performance.

Findings:

* Fast Delivery Average Review Score = 4.30
* Slow Delivery Average Review Score = 3.86

Statistical testing confirmed that delivery speed has a significant impact on customer satisfaction.

---

### 3. Revenue Growth Remains Positive

Growth-adjusted Monte Carlo forecasting estimated:

* Expected Monthly Revenue = 1.48M
* Forecast Range (90%) = 1.02M – 2.25M

The marketplace demonstrates continued growth momentum with manageable forecast uncertainty.

---

### 4. Customer Segmentation Revealed Retention Opportunities

RFM analysis identified:

* Champions
* Loyal Customers
* Potential Loyalists
* At Risk Customers
* Lost Customers

The largest revenue contribution comes from At Risk customers, indicating a significant opportunity for reactivation campaigns.

---

### 5. Revenue Is Broadly Distributed

Customer Lifetime Value analysis showed:

* Top 1% Customers → 17.05% Revenue
* Top 5% Customers → 35.38% Revenue
* Top 10% Customers → 47.40% Revenue

The marketplace does not follow a classic 80/20 Pareto distribution, suggesting lower customer concentration risk.

---

### 6. Predicting Repeat Customers

A Random Forest model was developed to predict repeat purchase behavior.

Performance:

* ROC-AUC = 0.763
* Precision = 57.7%
* Recall = 29.8%
* Optimized Threshold = 0.20

Most Important Predictors:

1. Delivery Days
2. Approval Latency Days
3. Total Payment Value
4. Price
5. Freight Value

These findings suggest that operational performance and transaction characteristics significantly influence customer retention.

---

## Business Recommendations

### Improve Customer Retention

* Loyalty Programs
* Personalized Recommendations
* Re-engagement Campaigns

### Optimize Delivery Operations

* Reduce Delivery Times
* Improve Order Processing Speed
* Monitor Logistics KPIs

### Focus on At Risk Customers

* Win-Back Campaigns
* Personalized Discounts
* Customer Reactivation Programs

### Expand High-Value Customer Programs

* VIP Benefits
* Premium Support
* Exclusive Promotions

---

## Technology Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SciPy
* Scikit-Learn
* XGBoost
* SHAP
* Jupyter Notebook

---

## Project Outcomes

This project demonstrates the application of:

* Business Analytics
* Statistical Inference
* Experimental Design
* Forecasting
* Customer Segmentation
* Machine Learning
* Explainable AI

to solve real-world e-commerce business problems and generate actionable business recommendations.
