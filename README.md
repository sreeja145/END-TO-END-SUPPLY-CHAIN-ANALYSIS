# Supply Chain Analytics & Delivery Risk Prediction

## 📌 Project Overview

This project analyzes end-to-end supply chain and delivery operations to identify the key factors contributing to late deliveries and understand their impact on profitability.

The analysis covers **172K+ orders** and combines exploratory data analysis, KPI analysis, root cause analysis, and machine learning to support data-driven logistics decisions.

## 🎯 Objectives

* Analyze delivery performance and identify bottlenecks
* Understand the key drivers of delivery delays
* Evaluate the relationship between delays and profitability
* Build a machine learning model to predict late deliveries
* Provide actionable recommendations to improve delivery performance

## 🔍 Key Findings

* **54.71%** of orders were delivered late.
* **Shipping Mode** was identified as the strongest factor associated with delivery delays.
* First Class had a **100% delay rate**, while Second Class had **79.8%**.
* August and September showed the highest delay rates at approximately **55.4%**.
* Customer segments showed similar delay patterns, indicating that delays were not primarily segment-specific.
* Payment-related order statuses such as **Payment Review** and **Pending Payment** were identified as potential operational bottlenecks.

## 🤖 Machine Learning

A **Random Forest Classifier** was developed to predict whether an order would be delayed.

### Approach

* Feature engineering
* Categorical feature encoding
* Stratified train-test split
* SMOTE for handling class imbalance
* Random Forest classification
* Model evaluation

The notebook reports approximately **74% accuracy** for the model.

## 🛠️ Skills & Technologies

* Python
* Pandas & NumPy
* Exploratory Data Analysis
* Supply Chain Analytics
* Root Cause Analysis
* Predictive Analytics
* Random Forest
* Feature Engineering
* SMOTE

## 📊 Business Recommendations

Based on the analysis:

1. Review carrier capacity and SLAs for First and Second Class shipping.
2. Introduce predictive alerts for high-risk orders.
3. Investigate payment-processing bottlenecks and automate escalation.
4. Prepare additional logistics capacity during peak months.
5. Re-evaluate shipping-mode assignment based on delivery reliability.

## 📁 Project Structure

```text
Supply-Chain-Analytics/
│
├── Supply Chain.ipynb
└── README.md
```

## 📌 Conclusion

The analysis demonstrates how supply chain data can be used to identify operational bottlenecks, quantify delivery performance, and support proactive logistics decisions. The predictive model further enables the identification of orders that are likely to experience delays.
