# SQL-Retail-Analysis
Retail Data Analysis with SQL (IBM Db2)

This project demonstrates end-to-end SQL-based analysis on a retail business dataset structured through an Entity-Relationship Diagram (ERD). It explores insights related to customer behavior, product performance, store revenue, and shipment operations using IBM Db2 SQL.

The analysis showcases the ability to write efficient, scalable SQL queries across a normalized schema to support data-driven decision making in a retail environment.

---

## Project Overview

- **Database Platform:** IBM Db2  
- **Schema Design:** Normalized relational structure with ERD  
- **Use Cases Covered:**
  - Customer segmentation and engagement  
  - Product and category performance  
  - Inventory gaps and promotion tracking  
  - Order revenue analysis  
  - Store and shipment optimization  

---

## Skills Applied

- Complex SQL query writing with **multi-table joins**, **aggregations**, and **subqueries**
- Mastery of **composite key relationships** and ERD interpretation
- Use of **IBM Db2-specific syntax**, such as `CURRENT DATE - n YEARS`, `FETCH FIRST`, `HAVING`, and `NULL` logic
- Structuring business logic into actionable, high-performance queries

---

## Key Business Analyses

### Customer & Engagement
- Identified customers aged 18+ who placed time-specific orders
- Mapped product category interest across age demographics
- Ranked customers by review activity and geographical data

### Shipment & Logistics
- Flagged shipments containing multiple orders to reduce delivery costs
- Filtered shipments delivered to specific geographic zones (e.g., Toronto via postal code patterning)

### Product Insights
- Detected products linked to a single category only
- Flagged brands offering only a single product (niche brand offerings)
- Tracked unpurchased products and promotional performance gaps

### Sales & Revenue
- Ranked high-value orders by sales totals
- Aggregated and compared monthly store revenue performance

### Warranty Coverage
- Identified categories with full warranty coverage across all products

---

## Repository Contents

| File | Description |
|------|-------------|
| `retail_sql_analysis_db2.sql` | Final, formatted SQL query set using IBM Db2 |
| `ERD.png` (optional) | Entity-Relationship Diagram used for schema design |
| `README.md` | Full documentation and project overview |

---

## Outcomes

- Translated real-world business requirements into optimized SQL logic
- Delivered insights aligned with operational, product, and marketing priorities
- Demonstrated end-to-end capability in relational data querying, structure understanding, and report-ready SQL outputs

---
