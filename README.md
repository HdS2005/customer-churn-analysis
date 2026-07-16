# 📉Customer Churn Intelligence

**End-to-end churn analytics: data cleaning → KPIs → prediction model → live dashboard**

[![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Wrangling-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-Logistic%20Regression-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![SQLite](https://img.shields.io/badge/SQLite-Database-07405E?style=flat-square&logo=sqlite&logoColor=white)](https://www.sqlite.org/)

</div>

<br>

<div align="center">
  <img width="2731" height="1551" alt="dashboard_preview" src="https://github.com/user-attachments/assets/b8043198-6fd0-4db2-9b70-c723cc5a8763" />
</div>

<br>

## ✨ What is this?

subscription behavior for **1,200 customers** to answer three questions every subscription business asks:

1. **Who's churning, and why?** — data cleaning, feature engineering & 12 business KPIs
2. **Who's about to churn?** — a Logistic Regression model with **87.1% accuracy**
3. **How do I keep watch?** — a fully interactive analytics dashboard built from scratch

No black boxes. Every number on the dashboard traces back to a real query on the underlying SQLite database.

<br>

## 🚀 Highlights

| | |
|---|---|
| 🎯 **Churn Rate** | 32.2% overall · 38.4% on Basic plan vs 24.0% on Premium |
| 💰 **Revenue at Risk** | ₹4.7K/month tied up in churned accounts |
| 🧠 **Prediction Model** | Logistic Regression · **87.1% accuracy** · balanced precision/recall |
| ⚠️ **High-Value At Risk** | 25 premium accounts flagged · ₹489/month exposure |
| 📊 **Top Churn Drivers** | Short tenure → Low lifetime value → High monthly charges → Monthly contract |

<br>

## 🖥️ Live Dashboard

The dashboard isn't just a static mockup — every control actually works:

- 🔍 **Live search** — filters the at-risk accounts table as you type (`⌘K` / `Ctrl+K` to focus)
- 📥 **Real CSV export** — one click downloads the current at-risk account list
- 🌗 **Dark / light theme toggle** — charts re-render with the new palette
- 🔔 **Notification center** — clear alerts, scroll-to-panel on click
- 🔄 **Refresh** — replays every animation: count-up KPIs, donut draw-in, line-chart draw-in

Open `churn_dashboard.html` directly in any browser — no server required.

<br>

## 📊 Key Insights

<table>
<tr><td>

**Customer Base**
- 1,200 total customers tracked
- 813 active · 387 churned
- Data spans 2018–2026

</td><td>

**Revenue**
- ARPU: ₹13.13
- Premium: ₹21.91 avg · Basic: ₹7.19 avg
- 574 support interactions logged

</td></tr>
<tr><td>

**Risk Segmentation**
- 707 Low risk
- 258 Medium risk
- 235 High risk

</td><td>

**Support & Escalations**
- 6.4% escalation rate
- 0.48 avg complaints/user
- +0.12 correlation: escalations ↔ churn

</td></tr>
</table>

<br>

## 🧠 Churn Prediction Model

A Logistic Regression classifier trained on genuine pre-cancellation signals only — `churn_score` and `churn_risk` were deliberately excluded since they're themselves churn-derived (no data leakage).

**Features used:** plan type, contract type, gender, monthly charges, CLTV, tenure, escalations, complaint count

| Metric | Score |
|---|---|
| Accuracy | 87.1% |
| Precision (Churned) | 0.83 |
| Recall (Churned) | 0.75 |
| F1-score (Churned) | 0.79 |

**Strongest churn drivers** (by model coefficient magnitude): short tenure, low CLTV, high monthly charges, and monthly (vs. annual) contracts.

<br>

## 🛠️ Tech Stack

**Analysis:** Python · Pandas · NumPy · Matplotlib · Seaborn · scikit-learn · Jupyter Notebook
**Data:** SQLite (3 relational tables — customer, subscription, support)
**Dashboard:** Vanilla HTML / CSS / JavaScript — hand-built SVG charts, zero chart libraries, zero dependencies

<br>

## 📁 Project Structure

```
retently-churn-analysis/
├── README.md
├── customer_churn.db          # SQLite database (customer / subscription / support)
├── churn_analysis.ipynb       # Full analysis: cleaning → KPIs → viz → model
├── churn_dashboard.html       # Interactive dashboard (open directly in browser)
└── assets/
    └── dashboard_preview.png
```

<br>

## ▶️ Getting Started

```bash
# clone the repo
git clone https://github.com/<your-username>/retently-churn-analysis.git
cd retently-churn-analysis

# install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# run the analysis
jupyter notebook churn_analysis.ipynb
```

To view the dashboard, just open `churn_dashboard.html` in your browser — that's it.

<br>

## 🗂️ Dataset Schema

| Table | Description |
|---|---|
| `db_customer` | Demographics — name, gender, country, state, DOB |
| `db_subscription` | Plan, contract type, charges, cancellation date/reason, CLTV, churn score |
| `db_support` | Complaint history, escalation flag, CSAT score |

<br>

## 🔮 Future Improvements

- [ ] Deploy the dashboard live (GitHub Pages / Vercel)
- [ ] Add cohort-based retention curves
- [ ] Experiment with tree-based models (Random Forest, XGBoost) for comparison
- [ ] Wire the dashboard to a live API instead of static data

<br>

## 📬 Connect

Built by **Harshdeep Singh**

Feel free to fork this, break it, and make it your own.

<br>

<div align="center">

⭐ **If this project helped you, consider giving it a star!** ⭐

</div>
