# SampleCust_Data

This project analyzes customer subscription data to understand patterns in engagement, spending behavior, and churn. Visualizations and feature analysis were performed to generate insights that can support business decisions.

---

## 📁 Dataset Summary

* **Total records:** 200 customers
* **Key columns:**

  * `Gender`, `Age`, `City`, `Income`, `SpendingScore`, `Subscription`
  * `Churn`, `SignupDate`, `VisitsPerMonth`

---

## 🎯 Project Goals

* Identify how subscription type impacts spending and churn
* Explore customer behavior based on visits, income, and tenure
* Visualize patterns using charts for better business understanding

---

## 🔍 Key Insights

### 1. **Subscription vs Spending & Churn**

* Gold users spend the most, but churn at 25%
* Basic users churn less (15%) despite slightly lower spending

### 2. **Tenure vs Churn**

* Churned users tend to have shorter tenure, but the difference is minor
* Boxplot shows overlapping distributions for churned vs active users

### 3. **Visits and Engagement**

* Most customers visit 1–3 times per month
* Slight positive link between visit frequency and spending

### 4. **Correlation Matrix**

* No strong correlation between numeric features
* Spending score and income are nearly independent

---

## 📊 Visuals Created

* **Boxplots:** Spending vs Subscription, Tenure vs Churn
* **Histograms:** Age, Income, Tenure
* **Violin plots:** Tenure across Subscription types
* **Heatmap:** Correlation matrix for numeric features
* **Dual-axis plot:** Avg Spending Score & Churn Rate by Subscription

---

## 🛠 Tools Used

* Python (Pandas, Seaborn, Matplotlib)
* Jupyter Notebook

