# 📊 Pensions Contribution Data Analysis

## 🏢 Project Overview

This project involves the exploratory and diagnostic analysis of contribution data from a **Pensions Contributions Company**. The goal is to extract business-relevant insights from user behavior, transaction outcomes, and cancellation patterns in order to guide operational and strategic decision-making.

The dataset includes records on:
- Contributor activity
- Subscription status
- Contribution cycles and amounts
- Transaction status and failure reasons
- Mobile network involvement
- Timestamps of user events

---

##  Business Questions Answered

1. **How many contributors have participated on the platform?**
2. **What proportion of contributors have canceled their subscriptions?**
3. **How soon do contributors cancel after joining?**
4. **Are most cancellations happening within a specific timeframe (e.g. within a day or week)?**
5. **What are the cancellation trends over time (monthly)?**
6. **Which mobile networks have the highest transaction failure rates?**
7. **What are the common reasons for failed contributions?**
8. **Are contributors mostly contributing the minimum amount?**
9. **What is the trend of total contributions over time?**
10. **Which day had the lowest successful transaction count since launch?**
11. **What were the reasons for failures on the lowest performing day?**

---

##  Types of Analysis Performed

- **Descriptive Analysis:** Overview of total users, cancellations, contributions, and transactions.
- **Network-Based Diagnostic Analysis:** Failure rate comparisons across mobile networks.
- **User Behavior Analysis:** Identifying users contributing close to the minimum required amount.
- **Time Series Analysis:** Tracking contribution volumes over time to identify peaks, drops, and anomalies.

---

## Key Visuals & Charts

- Bar chart: Cancellations per Join Month  
- Bar chart: Transaction failure rate by mobile network  
- Pie chart / table: Reasons for transaction failures  
- Bar chart: % of contributors contributing close to minimum  
- Line chart: Total contributions over time  
- Table: Day with lowest successful transactions  
- Table: Failure reasons for the lowest contribution day

---

## 💡 Business Value & Recommendations

- **Early Cancellations:** Over 90% of cancellations happen within the first 24 hours — signaling onboarding or trust issues.
- **High Failure Rates:** Certain networks show higher transaction failures; consider network partnerships or retries.
- **Minimum Contributions:** A significant number of users are contributing just around the required minimum; opportunity for up-sell or value addition.
- **Low Performing Days:** Operational or external issues affecting contributions on specific dates should be investigated.
- **Retention Interventions:** Implementing a drip communication or incentive model may improve early retention rates.

---

## 📂 Project Structure

- `contributions.csv` – Raw data
- `analysis_notebook.ipynb` – Step-by-step analysis
- `visuals/` – Saved plots and charts
- `README.md` – Project overview

---

## 🚀 Next Steps

- Implement predictive churn models.
- Build a dashboard for real-time monitoring.

---
