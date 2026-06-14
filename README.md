# 📡 Telecom Customer Churn Analytics

> **End-to-End Customer Analytics & Churn Prediction Solution**
> Exploratory Data Analysis · Customer Segmentation · Machine Learning · CLTV Analysis · Business Intelligence

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python\&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-orange?logo=scikit-learn\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas\&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter\&logoColor=white)
![Dataset](https://img.shields.io/badge/Dataset-IBM%20Telco-informational)

---

# Overview

This project analyzes customer churn behavior using the IBM Telco Customer Churn Dataset and demonstrates how data analytics and machine learning can help telecom companies improve customer retention.

The project combines business analytics and machine learning to transform raw telecom customer data into actionable retention strategies.

Key objectives include:

* Understanding customer churn patterns
* Identifying key churn drivers
* Predicting customer churn using machine learning
* Analyzing Customer Lifetime Value (CLTV)
* Segmenting customers into actionable groups
* Estimating revenue exposure from churn
* Building an executive-level business dashboard

---

# Dataset

**Source:** IBM Telco Customer Churn Dataset

**Records:** 7,043 Customers

**Features:** 50+ Customer Attributes

### Target Variable

* Churn Label (Yes / No)

### Available Information

* Customer Demographics
* Service Subscriptions
* Internet Services
* Contract Information
* Billing & Revenue Data
* Customer Satisfaction Metrics
* Customer Lifetime Value (CLTV)
* Churn Scores
* Churn Categories & Reasons

---

# Business Questions Addressed

### Customer Churn

* What is the overall churn rate?
* Which customer groups are most likely to churn?
* How does churn vary across contract types?
* How does churn differ by internet service?
* What are the most common churn reasons?
* What revenue is currently at risk?

### Customer Value

* Which customers generate the highest CLTV?
* Which segments contribute the most revenue?
* How does customer value vary across groups?

### Customer Segmentation

* Can customers be grouped into meaningful clusters?
* Which segments require retention efforts?
* Which segments represent the highest value?

### Machine Learning

* Can customer churn be predicted accurately?
* What are the strongest churn indicators?
* Which active customers are most at risk?

---

# Key Insights

* Approximately one-fourth of customers churned during the observed period.
* Month-to-Month contract customers showed significantly higher churn compared to long-term contract holders.
* Certain internet service categories exhibited higher churn behavior.
* Customer tenure strongly influenced retention outcomes.
* High-value customers can be identified through CLTV analysis and prioritized for retention.
* Customer clustering revealed distinct behavioral segments requiring different business strategies.

---

# Machine Learning Models

The following classification models were developed and evaluated:

### Logistic Regression

* Baseline churn prediction model
* Easy interpretation of customer risk factors

### Random Forest Classifier

* Ensemble learning approach
* Feature importance analysis

### Gradient Boosting Classifier

* Advanced boosting-based model
* Selected based on overall predictive performance

Model evaluation included:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC

---

# Project Structure

```text
telecom-customer-analytics/
│
├── Telecom_Customer_Analytics.ipynb
│
├── images/
│   ├── 01_initial_exploration.png
│   ├── 02_churn_analysis.png
│   ├── 03_cltv_analysis.png
│   ├── 04_feature_importance.png
│   ├── 05_customer_segmentation.png
│   └── 06_EXECUTIVE_DASHBOARD.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# Notebook Workflow

| Section   | Description                                    |
| --------- | ---------------------------------------------- |
| Section 0 | Environment Setup & Library Imports            |
| Section 1 | Data Loading & Business Understanding          |
| Section 2 | Exploratory Data Analysis                      |
| Section 3 | Data Cleaning & Feature Engineering            |
| Section 4 | Customer Churn Analysis                        |
| Section 5 | Machine Learning Modeling                      |
| Section 6 | Customer Segmentation & CLTV Analysis          |
| Section 7 | Executive Dashboard & Business Recommendations |

---

# Technologies Used

### Programming

* Python 3.10+

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn

### Machine Learning

* Scikit-Learn

  * Logistic Regression
  * Random Forest
  * Gradient Boosting
  * K-Means Clustering

### Development Environment

* Jupyter Notebook
* Google Colab

---

# Business Recommendations

Based on the analysis:

1. Prioritize Month-to-Month customers for retention campaigns.
2. Offer contract upgrade incentives to high-risk customers.
3. Focus retention efforts on high-CLTV customers.
4. Monitor churn-prone customer segments proactively.
5. Use churn prediction scores to trigger early intervention programs.
6. Develop personalized engagement strategies for different customer clusters.

---

# How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/telecom-customer-analytics.git
```

### Open Notebook

```bash
Telecom_Customer_Analytics.ipynb
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Analysis

Run notebook cells sequentially.

The dataset can be downloaded from the IBM Telco Customer Churn dataset source and uploaded when executing the notebook.

---

# Deliverables

* Customer Churn Analysis
* Feature Importance Analysis
* Customer Segmentation
* CLTV Analysis
* Revenue Risk Assessment
* Executive Dashboard
* Business Recommendations

---

# Author

**Kalpesh**

Data Analytics | Machine Learning | Business Intelligence

June 2026
