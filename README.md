# 📊 Personal Financial Advisor

## 📌 Project Overview

Managing personal finances is critical, yet many households struggle with budgeting and financial planning. Unexpected expenses, debt mismanagement, and lack of financial literacy contribute to financial stress, impacting long-term stability.

This project builds a **Personal Financial Advisor** tool that predicts financial stress levels and provides personalized budgeting recommendations. It aims to help individuals proactively manage finances, reducing debt accumulation and improving financial security. Using **machine learning**, the tool analyzes **income, expenses, and demographic factors** to classify financial risk and suggest actionable financial strategies.

---

## 🎯 Key Features

- **Financial Stress Prediction** → Identifies households at financial risk based on income, expenses, and demographics.
- **Spending Analysis** *→ Breaks down budget allocations to detect overspending trends.*
- **Personalized Budgeting Recommendations** → Provides tailored financial guidance to improve financial stability.

---

## 🔬 Data & Methodology

### 📂 Data Sources

**Source:** [**Consumer Expenditure Survey (CE) 2022**](https://www.bls.gov/cex/) data from the US Bureau of Labor Statistics

- **Interview Data** → Captures large recurring expenses, income levels, and household demographics.
- **Diary Data** → Logs frequent purchases such as food, personal care, and household supplies.
- **Key Variables Used**:
  - **Income Data** → Pre-tax and post-tax earnings.
  - **Spending Data** → Food, housing, discretionary, and essential expenses.
  - **Demographic Data** → Family size, age, marital status, urban vs. rural classification.

### 🛠 Data Processing & Analysis

- **Data Cleaning** → Processed missing values and standardized financial metrics.
- **Feature Engineering** → Created financial ratios and interaction terms to improve model accuracy.
- **Machine Learning Model** → Trained a Random Forest classifier to detect financial stress.
- **Evaluation Metrics** → Used accuracy and recall to assess model performance.

---

## 💻 Tech Stack

| Task                 | Tools & Methods             |
| -------------------- | --------------------------- |
| **Programming**      | Python                      |
| **Framework**        | Streamlit                   |
| **Data Processing**  | Pandas, NumPy               |
| **Machine Learning** | Scikit-learn, Random Forest |
| **Visualization**    | Matplotlib, Seaborn         |
| **Model Deployment** | Joblib, Streamlit Cloud     |

---

## 🚀 How to Use

1. **Run the Streamlit App**:
   ```bash
   streamlit run app.py
   ```
2. **Input Financial Data** → Provide details such as income, expenses, and household size.
3. **Get Insights**:
   - View **financial stress classification**.
   - Receive **personalized budgeting recommendations**.

---

## 📊 Visualizations & Insights

- **Feature Importance Graph** → Highlights key predictors of financial stress.
- **Financial Stress Probability** → Displays likelihood of financial instability.
- **Spending Breakdown** → Analyzes budget allocation across different categories.

---

## 🔎 Model Performance & Insights

- **Financial Stress Prediction** → Achieved **98% accuracy** in classifying high-risk households.
- **Recall Improvement** → Enhanced detection of high-stress cases by **7%** through feature engineering.
- **Budgeting Recommendations** → Provided spending adjustments and financial guidance tailored to individual income and expense patterns.

---

## 🔎 Recommendations

Based on analysis, the tool suggests:

- **Reducing discretionary spending** if high financial stress is detected.
- **Optimizing food and essential spending** for better financial balance.
- **Allocating a percentage of income to savings and debt reduction**.

---

## 🔧 Usage Instructions

- **GitHub Repository** → Clone the repository: `git clone https://github.com/vaishj001/personal_financial_advisor.git`
- **Streamlit App** → [Link to Hosted App]

---

## ⚠️ Assumptions & Limitations

- Assumes accurate **self-reported financial data**.
- Limited to **household-level** expenditure patterns.
- Model does not account for **external financial shocks** (e.g., medical emergencies, job loss).

---

## 🔮 Next Steps

- Deploy on **Streamlit Cloud** for public access.
- Fine-tune model with additional **socioeconomic indicators**.
- Expand recommendation logic using **real-time financial data**.
