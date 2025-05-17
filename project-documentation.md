# 📘 E-Commerce Customer Segmentation – Case Study

## Overview

This project explores a synthetic e-commerce dataset to uncover actionable insights into customer purchasing behavior, demographic patterns, and engagement drivers. The objective was to assist marketing and product teams in identifying key customer segments and tailoring their strategies accordingly.

**Key business questions addressed:**
- Which demographic segments are most valuable in terms of spending?
- How does ad engagement affect customer purchase frequency?
- What product categories are most popular by gender?
- How do devices and purchase channels influence shopping behavior?
- Which age groups show the highest brand loyalty?

---

## Data & Tools

- **Dataset Source:**  
  [Kaggle - E-commerce Consumer Behavior Dataset](https://www.kaggle.com/datasets/salahuddinahmedshuvo/ecommerce-consumer-behavior-analysis-data)

- **Tools Used:**  
  - Excel (data cleaning & transformation)  
  - Google BigQuery (SQL analysis)  
  - Tableau Public (interactive dashboard)  
  - GitHub (documentation)

---

## Data Preparation

- Applied filters to all columns to identify blank or unusual values.
- Cleaned special characters and normalized column names.
- Excluded inconsistent `Location` data.
- Fixed inconsistencies in fields like `Gender` and `Purchase_Channel` (e.g., correcting male to Male, in-store to In-Store).
- Binned `Age` into four groups:  
  **Young Adults (18–25)**, **Adults (26–35)**, **Middle-Aged (36–50)**, **Seniors (51+)**
- Cleaned unusual entries in the `Purchase_Category` column such as "Packages)" and "Travel & Leisure (Flights", which were corrected to "Packages" and "Travel & Leisure - Flights" using Find & Replace.
- Filters were re-applied to confirm all fields had consistent formatting, no critical blanks, and proper categorization. Sample checks and pivot table previews confirmed that the dataset is now analysis-ready.
- Verified data types and ensured compatibility with BigQuery.

---

## Analysis Approach

SQL queries in Google BigQuery were used to explore the following metrics:

- Customer distribution by age group and income level
- Average monthly purchases by ad engagement level
- Top product categories segmented by gender
- Device preferences across different shopping channels
- Brand loyalty scores across age groups

📄 [SQL queries used in the analysis](./sql_queries.txt)

---

## Key Insights

- **Adults (26–35)** made the most purchases per month and had the highest ad engagement.
- **Adult customers (26–35)** showed the highest brand loyalty and average spend.
- **Females** leaned toward jewelry & accessories and electronics, while **males** favored home appliances and gardening and outdoors.
- **Desktop users** primarily shopped online; **smartphone users** prefer a mix of both online and in-store.
- High **ad engagement** is not strongly correlated with increased purchase frequency.

---

## Dashboard

A fully interactive Tableau dashboard visualizes the analysis through:

- Bar charts for product category and ad engagement insights
- Heatmap comparing age group and income level vs. average purchase
- Stacked bars showing device and purchase channel distribution
- Brand loyalty chart segmented by age

🔗 [View Live Dashboard on Tableau Public](https://public.tableau.com/app/profile/christian.jerome.simbillo/viz/E-CommerceCustomerSegmentationDashboard/Dashboard1)

🖼️ [Dashboard chart screenshots](./e-commerce_customer_segmentation_dashboard.png)

---

## Business Recommendations

- 🎯 Focus digital ad campaigns on **adults with high engagement**.
- 📱 Improve mobile user experience to better support **desktop-driven shopping**.
- 💼 Launch loyalty programs aimed at **adult, middle-income and young-adult, high-income** customers.
- 👗 Refine marketing content based on **gender-specific product preferences**.
- 📊 Implement continuous tracking to refine audience segmentation over time.

---

## About

This case study was completed as part of the **Google Data Analytics Certification Program**. It demonstrates my ability to execute a complete analytics project—from asking business questions to preparing and analyzing data, visualizing insights, and recommending actions.

It also serves to showcase my transition into the field of data analytics. I am currently pursuing **entry-level roles in data analytics**, where I can apply the skills I’ve developed to solve real-world business problems using data-driven insights.


---
