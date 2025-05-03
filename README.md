# 💸 Personal Finance Tracker & Budget Optimization Dashboard

## 📌 Project Title  
**Personal Finance Tracker & Budget Optimization Dashboard (Power BI)**


![Screenshot 2025-05-02 125019](https://github.com/user-attachments/assets/e2716355-80a7-4b73-be7b-f95145c28be8)


---

## 📖 Description  
The Personal Finance Tracker is a powerful and interactive Power BI dashboard designed to help individuals, freelancers, and professionals monitor, analyze, and optimize their financial habits. From income and expenses to savings goals and category-based budgeting, this tool transforms personal finance into a visual, strategic, and data-driven experience.

It is built to answer real questions like:
- Am I saving or overspending?
- Where is most of my money going?
- What patterns exist in my monthly budget?
- How can I better manage my financial goals?

With smart DAX calculations, dynamic visuals, and performance summaries, it empowers users to take control of their money story.

---

## 📂 Table of Contents
- [Key Performance Indicators](#key-performance-indicators)  
- [DAX Measures & Logic Used](#dax-measures--logic-used)  
- [Business Questions Answered](#business-questions-answered)  
- [Insights & Data Highlights](#insights--data-highlights)  
- [Visual Features & Report Layout](#visual-features--report-layout)  
- [Actionable Insights for Users](#actionable-insights-for-users)  
- [Personal Finance Recommendations](#personal-finance-recommendations)  
- [Expected Outcomes](#expected-outcomes)  
- [Project Preview](#project-preview)  
- [Contact Me](#contact-me)

---

## 📊 Key Performance Indicators

| KPI                        | Example Value     |
|---------------------------|------------------|
| Total Income              | $35,000           |
| Total Expenses            | $28,400           |
| Total Savings             | $6,600            |
| Savings Rate              | 18.9%             |
| Highest Spending Category | Food & Groceries  |
| Month with Highest Expenses | April           |
| MoM Expense Change        | +7.2%             |
| Budget Surplus (May)      | +$550             |


---

## 🧠 DAX Measures & Logic Used
```DAX
Total Income = SUM('Finance'[Income])
Total Expenses = SUM('Finance'[Expense])
Savings = [Total Income] - [Total Expenses]
Savings Rate = DIVIDE([Savings], [Total Income])
MoM Change = ([Current Month] - [Previous Month]) / [Previous Month]
Category Percentage = DIVIDE(SUM('Finance'[Expense]), [Total Expenses])
```
These measures power all KPIs, breakdowns, and trend visualizations in the dashboard.

---

## ❓ Business Questions Answered
- What is my overall financial health (income vs expenses)?
- Where is most of my money going each month?
- Am I saving consistently or overspending?
- Which categories tend to exceed budget?
- How has my spending behavior changed over time?

---

## 📌 Insights & Data Highlights
- **Food & Groceries** consumed 20–25% of income monthly — the highest category.
- **April** had a spending spike due to travel and medical emergencies.
- **Entertainment & Subscriptions** often exceed limits.
- Savings of **$6,600** were achieved in 4 months by managing rent/utilities.
- Transport costs dropped **15%** after a switch to fuel-efficient options.

---

## 📈 Visual Features & Report Layout
- 📊 **Monthly Overview Cards** – Income, Expenses, Savings, Net Balance  
- 📈 **Trend Charts** – 6-Month Income vs Expense  
- 🧾 **Stacked Columns** – Expense by Category & Month  
- 📌 **Donut Charts** – Spending by Category  
- 🚦 **MoM Indicators** – Monthly % Changes, Surplus/Deficit  
- 🧭 **Slicers** – Filter by Month, Category, and Expense Type (Needs vs Wants)

---

## 💡 Actionable Insights for Users
1. Set caps on discretionary spending (e.g., shopping, entertainment).
2. Review subscriptions quarterly to remove unnecessary costs.
3. Automate monthly savings at income arrival.
4. Flag unusual expense spikes — classify as avoidable vs planned.

---

## 🧾 Personal Finance Recommendations
- Apply the **50/30/20 rule** to income allocation.
- Visualize and track your savings goals to build consistency.
- Use Power BI alerts to flag when near or above budget.
- Sync spending patterns with income surges (bonuses, side gigs).

---

## 🎯 Expected Outcomes
- 💰 Improved savings discipline and budget control  
- 📊 Better visibility into cash flow and monthly performance  
- 📅 Enhanced awareness of financial habits  
- 🧠 Confident, data-backed money decisions  

---

## 🎥 Project Preview  
[🔗 Finance Tracker Walkthrough (Google Drive)](https://app.powerbi.com/groups/me/reports/70f1f96d-b59f-450a-976f-e1603f6330a2/f5ac93b012a4a051db6e?experience=power-bi)

---

## 📬 Contact Me  
**Agba Frank Onwuchekwa**  
📧 Email: [Frankgodwin796@gmail.com](mailto:Frankgodwin796@gmail.com)  
🔗 LinkedIn: [Frank Agba](https://www.linkedin.com/in/frank-agba)

---

> ⚠️ *Disclaimer: This dashboard is built for educational and demo purposes. The data used is illustrative and not tied to real financial accounts.*
