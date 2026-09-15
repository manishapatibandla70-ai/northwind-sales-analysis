<img width="913" height="531" alt="nwss1" src="https://github.com/user-attachments/assets/0bffa3bf-3290-4ce5-a4d8-b75b91ea3589" />
<img width="901" height="508" alt="nwss2" src="https://github.com/user-attachments/assets/16129567-ad8d-4d0f-b198-98beb3476ac3" />
<img width="886" height="494" alt="nwss3" src="https://github.com/user-attachments/assets/b157cfbd-5af3-4a7e-b146-a364307024f5" />
<img width="908" height="508" alt="nwss4" src="https://github.com/user-attachments/assets/8c769f73-4f70-46a0-95de-eb510769103d" />
<img width="906" height="504" alt="nwss5" src="https://github.com/user-attachments/assets/cc74b3a8-63f1-4c1a-8b10-b21ac3ebe6fd" />
<img width="910" height="507" alt="nwss6" src="https://github.com/user-attachments/assets/ed26644f-5baa-4168-8949-c20326c11bbd" />
Northwind Traders: Sales & Business Insights Analysis
Author: Moksha Manisha
Date: March 12, 2026
Overview
This repository contains an end-to-end data analytics project evaluating the operational performance of Northwind Traders, a global wholesale specialty food importer and exporter. Utilizing Exploratory Data Analysis (EDA) and interactive Power BI dashboards, this project translates complex relational data into actionable business intelligence across customer operations, product revenue, workforce structure, and supplier networks.
Business Objective
The primary objective is to evaluate operational performance and driver behavior across Northwind Traders' core operational segments. Key focus areas include:
 * Uncovering customer order distributions, behavioral segmentation, and high-value accounts.
 * Assessing category-level revenue drivers, pricing structures, and inventory demand cycles.
 * Analyzing organizational workforce geography, job title distributions, and hiring timelines.
 * Mapping supplier geographical footprints, category coverage, and regional pricing trends.
Dataset & Relational Architecture
The project leverages eight core relational tables interconnected via primary and foreign keys (e.g., CustomerID, OrderID, ProductID, SupplierID):
| Table | Description |
|---|---|
| Customers | Stores customer company profiles, locations, and contact demographics. |
| Orders | Captures master order records, dates, and destination details. |
| Order Details | Contains granular line-item transactional data (quantities, unit prices, discounts). |
| Products | Maintains product catalog items, unit costs, stock levels, and supplier links. |
| Categories | Defines high-level product groupings. |
| Employees | Holds staff profile details, titles, hire dates, and regional assignments. |
| Suppliers | Tracks vendor company metadata and geographical origins. |
| Shippers | Contains shipping company profiles used for logistics. |
MECE Analytical Framework
To maintain a structured, non-overlapping analytical approach, the research adheres to a MECE (Mutually Exclusive, Collectively Exhaustive) framework:
                  ┌─────────────────────────────────────────────────┐
                  │    Northwind Traders MECE Analysis Framework    │
                  └────────────────────────┬────────────────────────┘
                                           │
         ┌──────────────────┬──────────────┴───────┬──────────────────┐
         ▼                  ▼                      ▼                  ▼
┌──────────────────┐┌───────────────┐     ┌──────────────────┐┌────────────────┐
│ Customer Metrics ││ Sales & Stock │     │ Workforce Intel  ││ Supplier Base  │
├──────────────────┤├───────────────┤     ├──────────────────┤├────────────────┤
│ • Orders/Customer││ • Top Revenue │     │ • Geo Distribution││ • Geo Coverage │
│ • Geo Patterns   ││ • Demand/Month│     │ • Role Breakdown ││ • Category Mix │
│ • Segmentation   ││ • Price/Stock │     │ • Hiring Trends  ││ • Price Spreads│
│ • Key Accounts   ││ • Outliers    │     └──────────────────┘└────────────────┘
└──────────────────┘└───────────────┘

Core Findings & Insights
 * Customer Concentration: A core segment of high-value repeat customers accounts for a disproportionately large share of total order volume and revenue.
 * Geographic Variations: Customer ordering density and spending profiles show strong clustering in specific geographic markets.
 * Revenue Drivers: Sales performance across categories is heavily skewed; a small subset of top-performing categories dominates earnings.
 * Seasonality & Demand: Product purchasing exhibits clear cyclical fluctuations across different months, highlighting key inventory planning windows.
 * Supplier Variance: Vendor pricing strategies and sourcing concentrations vary considerably across regions and product verticals.
Power BI Interactive Dashboard
An interactive Power BI dashboard accompanies this analysis, allowing stakeholders to dynamically slice and filter metrics:
 * Customer Demographics: Geo-mapping across countries/cities and segmentation by contact titles.
 * Sales Trends: Time-series tracking of order volume and total value distributions.
 * Product Diagnostics: Category revenue breakdown and stock-to-demand performance.
 * Operations & Supply: Employee role distribution alongside supplier pricing and distribution patterns.
Strategic Recommendations
 * Targeted Account Management: Focus sales and marketing resources on retaining and expanding high-value repeat customer accounts.
 * Dynamic Inventory Control: Align safety stock and reorder thresholds with seasonal demand fluctuations to eliminate stockouts and excess holding costs.
 * Product Portfolio Optimization: Review underperforming product lines to identify candidates for price adjustment, bundling, or phase-out.
 * Supply Chain Consolidation: Strengthen long-term partnerships with reliable, geographically advantaged suppliers to stabilize pricing.
