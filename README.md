# 📊 Customer Churn Analysis

A comprehensive Exploratory Data Analysis (EDA) project that investigates customer churn behavior using Python. The goal of this project is to identify the major factors contributing to customer churn and provide actionable business recommendations to improve customer retention.

---

## 📖 Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses. Losing existing customers directly impacts revenue and growth.

In this project, I performed an end-to-end data analysis on a customer churn dataset to uncover patterns, identify churn drivers, and generate business insights through data visualization.

---

## 🎯 Objectives

- Analyze customer behavior and churn patterns
- Clean and preprocess the dataset
- Perform Exploratory Data Analysis (EDA)
- Visualize important business metrics
- Identify factors influencing customer churn
- Provide business recommendations to reduce churn

---

## 📂 Dataset

**Dataset:** Customer Churn Dataset

The dataset contains customer demographic information, service details, contract information, billing information, and churn status.

Example Features:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## 📊 Project Workflow

### 1. Data Collection

- Imported customer churn dataset

### 2. Data Cleaning

- Removed duplicate values
- Handled missing values
- Converted data types
- Checked data consistency

### 3. Exploratory Data Analysis (EDA)

Performed analysis on:

- Customer Demographics
- Contract Types
- Internet Services
- Payment Methods
- Monthly Charges
- Total Charges
- Customer Tenure

### 4. Data Visualization

Created multiple visualizations using Matplotlib and Seaborn to understand customer behavior.

---

# 📈 Visualizations

### Customer Churn Distribution

<p align="center">
<img src="images/churn_distribution.png" width="700">
</p>

---

### Correlation Heatmap

<p align="center">
<img src="images/correlation_heatmap.png" width="700">
</p>

---

### Monthly Charges vs Churn

<p align="center">
<img src="images/monthlycharges_vs_churn.png" width="700">
</p>

---

### Tenure vs Churn

<p align="center">
<img src="images/tenure_vs_churn.png" width="700">
</p>

---

## 🔍 Key Insights

- Customers with month-to-month contracts have a significantly higher churn rate.
- Customers with longer tenure are less likely to churn.
- Higher monthly charges are associated with increased churn probability.
- Fiber Optic internet users show relatively higher churn.
- Electronic Check payment method has a higher churn percentage.
- Customers using long-term contracts are more likely to stay with the company.
- Senior citizens exhibit a slightly higher churn rate.
- Customer retention improves as service duration increases.

---

## 💼 Business Recommendations

- Offer discounts on yearly and two-year contracts.
- Improve customer onboarding during the first few months.
- Introduce loyalty rewards for long-term customers.
- Provide personalized retention offers to high-risk customers.
- Review pricing strategy for customers with high monthly charges.
- Improve customer support for Fiber Optic users.
- Build targeted retention campaigns based on customer segments.

---

## 📁 Project Structure

```

customer-churn-analysis/
│
├── Customer\_Churn\_Analysis.ipynb
├── README.md
├── requirements.txt
│
├── data/
│   └── customer_churn.csv
│
└── images/
├── churn_distribution.png
├── correlation_heatmap.png
├── tenure_vs_churn.png
└── monthlycharges_vs_churn.png

```

---

## 🚀 Future Improvements

- Build a Machine Learning model to predict customer churn
- Deploy an interactive Power BI dashboard
- Perform Feature Engineering
- Compare multiple Machine Learning algorithms
- Deploy the project as a web application

---

## 📌 Requirements

Install required libraries using:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

```bash
git clone https://github.com/HdS2005/customer-churn-analysis.git

cd customer-churn-analysis

jupyter notebook
```

---

## 📬 Contact

**Harshdeep Singh**

📧 Email: harshdeepsingh4694@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/harshdeep-singh07/

---

## ⭐ If you found this project useful, consider giving it a star.
