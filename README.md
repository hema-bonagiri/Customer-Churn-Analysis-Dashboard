# Customer Churn Analysis Dashboard

## Project Overview

**Customer Churn Analysis Dashboard** is an interactive Power BI project developed to analyze customer churn in the telecommunications industry.

The dashboard analyzes **7,043 customers across 21 attributes**, covering customer demographics, tenure, service subscriptions, contracts, payment methods, and billing information to identify churn patterns and high-risk customer segments.

---

## Problem Statement

Customer churn can negatively impact customer retention and recurring revenue. The business needs to understand **which customers are more likely to stop using the telecom service and what factors are associated with higher churn**.

This project analyzes customer behavior across tenure, services, contracts, payment methods, and billing patterns to identify important churn drivers.

---

## Objectives

- Analyze overall customer churn and identify high-churn segments.
- Understand churn patterns across customer tenure and demographics.
- Analyze the relationship between service subscriptions and churn.
- Compare churn across contract types and payment methods.
- Generate actionable insights to support customer-retention strategies.

---

## Dataset

| Attribute | Details |
|---|---|
| **Dataset** | Telco Customer Churn |
| **Records** | 7,043 customers |
| **Attributes** | 21 |
| **Format** | CSV |

The dataset contains information about:

- Customer demographics
- Tenure
- Phone and internet services
- Additional services
- Contract types
- Payment methods
- Monthly and total charges
- Churn status

**Churn = Yes:** Customer stopped using the telecom service.  
**Churn = No:** Customer continued using the telecom service.

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI** | Dashboard development and visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | KPI and analytical calculations |
| **CSV** | Source dataset |

---

## Data Preparation

Used **Power Query** to prepare the raw telecom customer data for analysis by performing data validation, cleaning, and transformation. Created analytical fields such as **Tenure Range** and **Service Count** to support customer segmentation and churn analysis.

---

## DAX & KPI Development

Created DAX measures to support dynamic dashboard analysis and KPI reporting.

### Key KPIs

- Total Customers
- Churned Customers
- Churn Rate
- Average Monthly Charges
- Average Tenure
- Average Services per Customer
- Retained Revenue
- Lost Revenue

---

## Power BI Dashboard

The dashboard consists of **three analytical pages** designed to provide different perspectives of customer churn.

### Customer Overview & Demographics

Provides an overview of customer demographics, tenure, charges, and churn behavior.

### Service Subscription Analysis

Analyzes service adoption and churn across service categories and service counts.

### Contract, Billing & Churn Drivers

Analyzes contract types, payment methods, revenue contribution, and key churn drivers.

---

## Dashboard Screenshots

### Customer Overview & Demographics

![Customer Overview](Customer%20Overview.png)

### Service Subscription Analysis

![Service Analysis](Service%20Analysis.png)

### Contract, Billing & Churn Drivers

![Churn Analysis](Churn%20Analysis.png)

---

## Key Business Insights

- Overall customer churn rate is **26.54%**.
- Customers with **0–12 months of tenure have the highest churn rate at 47.44%**, with churn declining as tenure increases.
- **Month-to-month customers have the highest churn rate at 42.71%**.
- **Fiber Optic customers have the highest internet-service churn at 41.89%**.
- **Electronic-check users have the highest payment-method churn at 45.29%**.
- **Month-to-month + Fiber Optic customers have the highest combined churn rate at 54.61%**.
- Churned customers account for approximately **2.86M in lost revenue**.

---

## Business Recommendations

Based on the analysis:

- Strengthen onboarding and engagement for newly acquired customers.
- Prioritize retention strategies for high-churn customer segments.
- Encourage suitable long-term contract adoption through relevant offers.
- Investigate factors contributing to higher churn among Fiber Optic customers.
- Review potential billing or payment-related issues among electronic-check users.

---

## Skills Demonstrated

**Power BI | Power Query | DAX | Data Cleaning | Data Transformation | Data Visualization | KPI Development | Dashboard Development | Churn Analysis | Business Intelligence**

---

## Conclusion

The analysis identifies **early-tenure customers, month-to-month contract customers, Fiber Optic users, and electronic-check users** as important high-churn segments.

The Power BI dashboard provides an interactive view of these patterns and supports **data-driven customer-retention decisions**.

---

## Author

**Hema Bonagiri**
