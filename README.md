# 📊 Customer Churn Analysis & Prediction

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![SQLite](https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-success?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. Losing existing customers directly impacts revenue and long-term growth.

This project analyzes customer behavior, identifies major churn drivers, visualizes business insights, and builds a machine learning model capable of predicting customer churn.

The complete workflow includes:

- Data Cleaning
- Data Preparation
- Exploratory Data Analysis
- Business KPI Analysis
- Customer Segmentation
- Churn Prediction using Machine Learning
- Business Recommendations

---

# 🎯 Business Problem

The company wants to answer questions such as:

- Which customers are most likely to churn?
- Which subscription plans have the highest churn?
- How do contracts influence customer retention?
- Which regions require immediate attention?
- Which business factors contribute the most to churn?
- How much revenue is at risk due to customer churn?

---

# 📂 Dataset

The project uses a synthetic telecom subscription database containing realistic customer information.

### Database Tables

| Table | Description |
|--------|-------------|
| **db_customer** | Customer demographics |
| **db_subscription** | Subscription & billing details |
| **db_support** | Customer support history |

### Dataset Size

| Metric | Value |
|---------|-------|
| Customers | **1,200** |
| Subscriptions | **1,200** |
| Support Tickets | **574** |

---

# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- SQLite
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

# 🧹 Data Cleaning

The dataset was cleaned by performing:

- Missing value treatment
- Duplicate removal
- Country standardization
- Gender normalization
- Datatype conversions
- Feature engineering
- Table merging
- Churn label creation

---

# 📈 Business KPIs

The analysis includes:

- Overall Churn Rate
- Customer Retention Rate
- Average Revenue Per User (ARPU)
- Revenue at Risk
- Average Customer Tenure
- Churn by Subscription Plan
- Churn by Contract Type
- Escalation Rate
- Complaint Analysis
- High-Value Customers at Risk
- Churn Risk Segmentation
- State-wise Churn Analysis

---

# 📊 Visualizations

The notebook contains multiple business-focused visualizations including:

- Monthly Churn Trend
- Churn by Subscription Plan
- Churn by Contract Type
- State-wise Churn Analysis
- Correlation Heatmap
- Customer Segmentation
- Executive Dashboard
- Revenue Impact Analysis

---

# 🤖 Machine Learning

A Logistic Regression model was developed to predict customer churn.

### Workflow

- Feature Selection
- Label Encoding
- Train/Test Split
- Feature Scaling
- Logistic Regression
- Model Evaluation
- Feature Importance Analysis

### Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | **87%** |

---

# 📊 Key Insights

- Monthly contracts have significantly higher churn than annual contracts.
- Basic plan customers are more likely to churn.
- Customers with support escalations show higher churn probability.
- Short customer tenure strongly correlates with churn.
- High-value customers contribute the largest revenue risk.

---

# 💡 Business Recommendations

- Offer discounts for annual subscriptions.
- Build retention campaigns for high-risk customers.
- Reduce customer support response time.
- Monitor customers with repeated escalations.
- Create personalized offers for premium customers.

---

# 📁 Project Structure

```
Customer-Churn-Analysis/
│
├── churn_analysis.ipynb
├── customer_churn.db
├── README.md
├── requirements.txt
└── images/
```

---

# 📸 Dashboard Preview

> Add screenshots here after uploading them.

```
images/dashboard.png
images/model.png
images/heatmap.png
```

---

# 🚀 How to Run

```bash
git clone https://github.com/yourusername/customer-churn-analysis.git

cd customer-churn-analysis

pip install -r requirements.txt

jupyter notebook
```

Open:

```
churn_analysis.ipynb
```

Run all cells.

---

# 📌 Future Improvements

- XGBoost Model
- Random Forest Comparison
- Interactive Dashboard
- Power BI Dashboard
- Streamlit Deployment
- Customer Lifetime Value Forecasting

---

# 👨‍💻 Author

**Harshdeep Singh**

B.Tech Computer Science

Aspiring Data Analyst

---

## ⭐ If you found this project useful, consider giving it a star.
