# Superstore Sales Analysis & Dashboard 🚀

![Project Status](https://img.shields.io/badge/Status-Completed-success)
![Tools](https://img.shields.io/badge/Tools-Python%20|%20Tableau-blue)

## 📌 Project Overview
**Analyst:** Calvin Leo
**Dataset:** Sample - Superstore (US Retail Data)

This project focuses on analyzing retail sales data to identify **profit leaks** and **strategic growth opportunities**. The analysis follows an end-to-end data pipeline, starting from data cleaning and exploratory analysis using **Python**, culminating in an interactive business dashboard using **Tableau**.

---

## 📊 Interactive Dashboard
The final insights are visualized in an interactive executive dashboard.
👉 **[Click here to view the Dashboard on Tableau Public](https://public.tableau.com/app/profile/calvin.leo8449/viz/SuperstoreSalesExecutiveDashboard_17635055417900/Dashboard1)**

---

## 🛠️ Tech Stack & Workflow
The project was executed using the following workflow:

1.  **Data Cleaning & Preprocessing (Python/Pandas):**
    * Data type conversion (handling datetime formats).
    * Duplicate removal and missing value handling.
    * Feature Engineering (Creating `Order Month` & `Order Year` columns).
2.  **Exploratory Data Analysis (Python/Matplotlib & Seaborn):**
    * Monthly sales trend analysis (Seasonality detection).
    * Correlation analysis between Discount and Profit.
    * Identifying underperforming product categories.
3.  **Data Visualization (Tableau):**
    * Geographical mapping to track regional profitability.
    * Interactive dashboard design for KPI monitoring.

---

## 💡 Key Findings (Insights)
Based on the data analysis, several critical business insights were uncovered:

1.  **The "Discount Trap":**
    * There is a strong negative correlation between discount rates and profit margins.
    * **Finding:** Discounts above **20%** consistently result in financial losses. The current discounting strategy is detrimental to the bottom line.
2.  **Unprofitable Categories:**
    * The **Furniture** category, specifically the **"Tables"** sub-category, generates high sales volume but suffers from minimal or negative profit. This suggests issues with high operational/shipping costs or thin margins.
3.  **Geographical Losses:**
    * **Texas**, **Ohio**, and **Pennsylvania** were identified as the top loss-making states, dragging down the overall performance of their respective regions.

---

## 📈 Business Recommendations
To improve profitability, the following strategies are recommended:

* **Revise Discount Strategy:** Cap discounts at a maximum of 20% to preserve profit margins, especially for standalone orders.
* **Re-evaluate Furniture Strategy:** Conduct a cost-benefit analysis on the "Tables" sub-category. Consider increasing prices, optimizing shipping logistics, or discontinuing highly unprofitable SKUs.
* **Regional Optimization:** Investigate operational bottlenecks in Texas and Ohio. Shift marketing focus in these regions towards high-margin products (e.g., Technology) to offset logistics costs.

---

## 📂 Repository Structure
* `Superstore_Analysis.ipynb`: Jupyter Notebook containing Python code for cleaning & EDA.
* `Superstore_Cleaned.csv`: The processed dataset used for dashboarding.
* `README.md`: Project documentation.

---

## 🤝 Connect with Me
If you have any questions or feedback regarding this analysis, feel free to reach out!

* **LinkedIn:** [www.linkedin.com/in/calvin-leo7234]
* **Tableau Public:** [Calvin Leo](https://public.tableau.com/app/profile/calvin.leo8449)
