# 📊 Sprint 10 – Commercial Performance Dashboard

Interactive Power BI dashboard developed as part of the Data Analysis Bootcamp.

The project analyzes the commercial performance of **Andes Retail Group**, a retail company operating in Peru, Chile, and Colombia, using transactional data from 2024–2025.

The objective was to transform transactional data into a clear and interactive dashboard that supports business decision-making around **revenue, profitability, customers, products, geography, and seasonality**.

---

## 🎯 Business Objective

The dashboard was designed to answer key business questions:

* How did total revenue evolve between 2024 and 2025?
* Which customer segments contribute the most revenue and profit?
* Which product categories have the greatest impact on the business?
* Are there relevant differences between countries or regions?
* What seasonal patterns can be observed throughout the year?
* Where might there be opportunities for commercial improvement?

---

## 📊 Dashboard

### Executive Overview

The Overview provides a high-level view of the company's commercial performance through key KPIs, temporal trends, and comparisons across countries and product categories.

![Executive Overview](https://drive.google.com/file/d/1FmWHRdSU6sfwd4_GJQw5tdB_YwFNCjaP/view?usp=sharing)

### Detailed Analysis

The Detail view allows deeper exploration of profitability, seasonality, customer segments, and product categories.

![Detailed Analysis](https://drive.google.com/file/d/1b_pRS4ahhn2frGQOGBLzh6MEYEYloWAC/view?usp=sharing)

---

## 📌 Key KPIs

The Executive Overview includes four main performance indicators:

* **Total Revenue**
* **Total Profit**
* **Average Profit Margin**
* **Total Orders**

These KPIs provide a quick assessment of the overall commercial performance before exploring the detailed analysis.

---

## 🔍 Key Business Insights

* **Peru** generated the highest revenue among the analyzed countries.
* **Summer** showed the strongest commercial performance, highlighting a seasonal component in the business.
* Profitability varies across **customer segments**, allowing the business to identify segments with greater contribution to total profit.
* **Product categories** also show differences in their contribution to profitability.
* Interactive filters allow users to explore performance by **date and country** and identify specific patterns within the business.

---

## 🧠 Storytelling Approach

The dashboard was structured using the **SCQA (Situation, Complication, Question, Answer)** framework to transform the analysis into a clear business narrative.

### Situation

Andes Retail Group needs a consolidated view of its commercial performance across multiple countries, products, and customer segments.

### Complication

Overall business indicators do not fully explain differences in profitability, geography, customer segments, and seasonality.

### Question

Which areas of the business contribute most to revenue and profitability, and where are there opportunities for improvement?

### Answer

The dashboard provides an interactive view of commercial performance, highlighting differences across countries, seasons, customer segments, and product categories to support data-driven decision-making.

---

## 🛠️ Data Preparation

The project included:

* Importing and validating the transactional dataset.
* Reviewing column data types and data quality.
* Validating records and missing values.
* Creating calculated/conditional fields for additional business analysis.
* Preparing the data for visualization and dashboard development.

---

## 🎨 Dashboard Design

The dashboard was designed following basic data visualization and business intelligence principles:

* Clear visual hierarchy.
* Limited number of visualizations.
* Consistent typography and formatting.
* Focus on business questions rather than isolated charts.
* Interactive filters and visual interactions.
* Separation between executive overview and detailed analysis.
* Use of visual storytelling to guide the user through the information.

---

## ▶️ How to Use

The main deliverable is the Power BI `.pbix` file.

To explore the dashboard:

1. Download the `.pbix` file from the `dashboard/` folder.
2. Open it using **Power BI Desktop**.
3. Navigate between the **Overview** and **Detail** pages.
4. Use the available filters to explore the data dynamically.

---

## 📁 Repository Structure

```text
sprint10-final-project/
│
├── README.md
│
├── dashboard/
│   └── Andes_Retail_Group.pbix
│
├── images/
│   ├── overview_dashboard.png
│   ├── detail_dashboard.png
│   └── dashboard_preview.png
│
└── data/
    └── README.md
```

The original dataset is not included in this repository if redistribution is not permitted.

---

## 🛠️ Tools & Technologies

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Microsoft Excel**

---

## 🚀 Future Improvements

Potential extensions to the dashboard include:

* Adding drill-through pages for deeper customer and product analysis.
* Incorporating sales and profit forecasting.
* Adding customer retention and lifetime value metrics.
* Creating dynamic tooltips with additional business metrics.
* Expanding geographic analysis.
* Implementing more advanced Power BI features such as Row-Level Security (RLS).

---

## 📌 Project Context

This project was developed as part of **Sprint 10 – Build Clear Visual Stories with Charts** in the Data Analysis Bootcamp.

The focus of the sprint was not only on creating functional visualizations, but on learning how to transform data into a **clear, interactive, and business-oriented visual story**.
