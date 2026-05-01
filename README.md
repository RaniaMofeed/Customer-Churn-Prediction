# 📊 Telco Customer Churn Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green) ![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-orange)

## 🔍 Project Overview
Analysis of **7,032 telecom customers** to identify key drivers of customer churn and provide actionable business recommendations.

**Business Question:** Why are customers leaving, and what can the company do to retain them?

---

## 📁 Dataset
- **Source:** [Telco Customer Churn — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Size:** 7,032 customers × 21 features
- **Target:** Churn (Yes/No)

---

## 🛠️ Tools & Libraries
| Tool | Usage |
|------|-------|
| Python | Core language |
| Pandas | Data cleaning & analysis |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| Jupyter Notebook | Development environment |

---

## 🔑 Key Findings

### 📊 Overview
- Overall churn rate: **26.5%** (1 in 4 customers leaves)
- Dataset is imbalanced: 73.5% stayed vs 26.5% churned

### 🔴 Top Churn Drivers
| Factor | Correlation | Insight |
|--------|------------|--------|
| Monthly Charges | +0.19 | Higher charges → higher churn |
| Paperless Billing | +0.19 | Tech-savvy users compare prices easily |
| Senior Citizen | +0.15 | Need more support |
| Month-to-month contract | — | ~42% churn vs 3% for 2-year contracts |
| New customers (0–12 mo) | — | ~47% churn rate in first year |

### 🟢 Retention Factors
| Factor | Correlation | Insight |
|--------|------------|--------|
| Partner | -0.15 | Shared plans increase loyalty |
| Streaming Services | -0.04 | More services = more engagement |
| Long-term contracts | — | 2-year contracts = 3% churn only |

---

## 💡 Business Recommendations
1. **Loyalty discounts** for high monthly charge customers after 6 months
2. **Onboarding program** targeting new customers in their first year
3. **Promote family/partner plans** — strongest retention factor found
4. **Proactive retention campaigns** for paperless billing segment

---

## 📂 Project Structure
```
telco-churn-analysis/
│
├── telco_churn_analysis.ipynb   # Main analysis notebook
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── churn_distribution.png
├── churn_by_contract.png
├── churn_by_tenure.png
├── churn_by_charges.png
├── churn_correlation.png
└── README.md
```

---

*Analysis by Rania Mofeed | [LinkedIn](https://www.linkedin.com/in/raniamofeed) | [GitHub](https://github.com/RaniaMofeed)*
