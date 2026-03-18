# Marketing-Insights-Report
An Executive-level Power BI dashboard transforming raw marketing data into strategic business insights. Features advanced DAX KPIs, deep-dive customer segmentation, and a monochromatic professional UI designed for stakeholder decision-making.

# 📊 Marketing Performance & Customer Insights Executive Dashboard

## 📝 Project Overview
This project transforms a complex marketing dataset of 2,240 customers into a streamlined, **Executive-Ready Business Intelligence tool**. Using Power BI, I developed a monochromatic dashboard that allows stakeholders to identify revenue drivers, evaluate campaign success, and segment customers with precision.

![Dashboard Overview](new%20int%20dash.png)

---

## 🎯 Problem Statement
The marketing department faced "data silos" and fragmented reporting. Stakeholders could not easily determine:
* Which product categories contributed most to the bottom line.
* The ROI of different sales channels (Web, Catalog, Store).
* Which customer demographics (Education/Marital Status) were the most profitable.

**The Goal:** Build a unified, interactive interface that reduces manual reporting time and provides clear, actionable insights for budget reallocation.

---

## 🛠️ Procedures & Methodology

### 1. Data Cleaning (Power Query)
* **Standardization:** Fixed missing values in the `Income` field to ensure accurate averages.
* **Feature Engineering:** Created conditional columns to group `Age` into segments (20-35, 36-50, 50+) and standardized `Education` labels.
* **Date Intelligence:** Transformed raw date strings into a proper Date Table to enable monthly and yearly trend analysis.

### 2. Data Modeling & DAX
* Created a clean star-schema-ready model to ensure high-performance filtering.
* **Key Measures:** Developed DAX formulas for `Total Revenue`, `Total Customers`, and `Average Spend per Category`.

### 3. UI/UX Design (Executive Standard)
* **Monochromatic Palette:** Applied a "Midnight Blue" theme to reduce cognitive load and focus attention on the data.
* **White Card Layout:** Utilized a light-grey canvas with white visual containers to create a modern, structured "Executive" feel.

---

## 💡 Key Insights
* **Revenue Titan:** **Wines** and **Meat Products** are the core business drivers, accounting for over **70% of total revenue**.
* **High-Value Persona:** Customers with a **Graduate** level of education who are **Married/Together** represent the most significant spending demographic.
* **Channel Trends:** While **Store Purchases** lead in volume, **Web Sales** show consistent growth, peaking mid-year.
* **Campaign Gap:** Data revealed that households with small children had significantly lower campaign response rates, indicating a need for a shift in messaging for that segment.

---

## 🚀 Strategic Recommendations
1. **Premium Bundling:** Launch a "Premium Wine & Meat" pairing campaign specifically targeting the high-income **Graduate** segment.
2. **Digital Transition:** Invest in a **Web-Exclusive Loyalty Program** to capitalize on the growing trend of online shopping.
3. **Messaging Pivot:** Re-evaluate the "Family" marketing strategy. Current promotional offers are not resonating with households with children; a shift toward value-based family messaging or a budget reallocation is recommended.
4. **Inventory Management:** Prioritize stock levels for top-tier categories (Wines/Meats) during identified peak months to prevent revenue loss.

---

## 📂 Repository Structure
* `Marketing_Performance_Report.pbix`: The full Power BI report.
* `/Data`: The raw dataset used for the analysis.
* `new int dash.png`: High-resolution screenshot of the final dashboard.

---
**Author:** Mercy Enujuba  
**Role:** Data Analyst
