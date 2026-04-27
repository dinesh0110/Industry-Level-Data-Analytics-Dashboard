# Industry-Level Data Analytics Dashboard

An end-to-end **Power BI** analytics project built on the Olist e-commerce dataset, designed to turn raw transactional data into business-ready insights across revenue, customer behavior, delivery performance, payments, seller performance, and product categories. The uploaded dashboard PDF shows a multi-page report with KPI cards, trend views, category analysis, geographic breakdowns, delivery SLA tracking, review analytics, payment insights, seller analysis, and drillthrough reporting.[1]

## Project files

- [Power BI Dashboard (.pbix)](https://github.com/dinesh0110/Industry-Level-Data-Analytics-Dashboard/blob/main/Industry-Level%20Data%20Analytics%20Dashboard.pbix)
- [Dashboard Report (.pdf)](https://github.com/dinesh0110/Industry-Level-Data-Analytics-Dashboard/blob/main/Industry-Level%20Data%20Analytics%20Dashboard.pdf)
- [Dataset (.zip)](https://github.com/dinesh0110/Industry-Level-Data-Analytics-Dashboard/blob/main/Olist_dataset.zip)

## Project overview

This project was developed to simulate an **industry-level business intelligence solution** using Power BI and PostgreSQL-backed analytics modeling. The dashboard tracks core business KPIs such as total revenue, total orders, total customers, on-time delivery percentage, average order value, average rating, and year-over-year growth.[1]

The report is structured as an interactive multi-page dashboard covering:

- Executive overview with top-level KPIs and revenue trends.[1]
- Revenue analysis by category, month, and year.[1]
- Customer geography analysis by state and city.[1]
- Delivery performance and late-order monitoring.[1]
- Review and rating analysis.[1]
- Payment behavior and installment analysis.[1]
- Seller performance tracking.[1]
- Drillthrough analysis for category-level deep dives.[1]

## Business questions answered

This dashboard helps answer questions such as:

- How is revenue trending over time?[1]
- Which product categories generate the highest revenue and order volume?[1]
- Which customer states and cities contribute the most revenue?[1]
- What percentage of orders are delivered on time, and where are delays highest?[1]
- How do ratings vary by category and by late vs on-time delivery?[1]
- Which payment methods dominate overall order value?[1]
- Which sellers contribute the most revenue?[1]

## Key highlights

- Total revenue: **$14.21M**.[1]
- Total orders: **98.67K**.[1]
- Total customers: **95.42K**.[1]
- On-time delivery rate: **93.23%**.[1]
- Average order value: **144.01**.[1]
- Average rating: **4.03**.[1]
- Year-over-year growth: **253.07%**.[1]
- Delivered orders account for **97.78%** of order status share.[1]

## Data model and engineering

The analytical layer behind the dashboard was designed using a **star schema approach** to improve reporting performance and simplify downstream analysis. PostgreSQL views were created to separate fact and dimension logic for products, orders, reviews, payments, and sales reporting, which is a common pattern in Power BI and warehouse-style analytics projects.[2][1]

Core engineering work included:

- Cleaning and transforming source data using **Power Query**.
- Building reusable SQL views for business reporting.
- Designing fact and dimension-style tables for efficient analysis.
- Using both **Import** and **DirectQuery** approaches depending on reporting needs.
- Creating DAX measures to support KPIs, trends, ratios, and drillthrough logic.

## Dashboard pages

### 1. Executive overview

This page summarizes the business using KPI cards and high-level visuals for revenue trends, orders by month, revenue by state, top categories by revenue, and order status distribution.[1]

### 2. Revenue analysis

This section compares revenue against last year, tracks year-to-date performance, shows rolling 30-day revenue, and breaks down revenue, orders, and AOV by category across years.[1]

### 3. Category performance

This page analyzes category revenue share, average order value vs order count, top categories by average rating, and category-level summary metrics.[1]

### 4. Customer geography

This section highlights revenue contribution by customer state and city, along with category-level revenue patterns across regions.[1]

### 5. Delivery performance

This page focuses on late orders, on-time percentage, monthly delay trends, average delivery days by category, and late-order share by customer state.[1]

### 6. Ratings and reviews

This page tracks average rating, positive and negative review share, rating distribution, and differences in rating between late and on-time deliveries.[1]

### 7. Payment analysis

This section shows payment type share, average installments by payment method, and overall payment value trends over time.[1]

### 8. Seller performance

This page analyzes total sellers, revenue per seller, top sellers by revenue, and seller-state-based category contributions.[1]

### 9. Drillthrough analysis

The drillthrough page enables deep analysis for individual categories, combining revenue trend, customer state contribution, AOV, ratings, order count, and on-time performance in one focused view.[1]

## Tools and technologies

| Category | Tools Used |
|---|---|
| Visualization | Power BI |
| Data transformation | Power Query |
| Database | PostgreSQL |
| Querying | SQL |
| Modeling | Star Schema |
| Metrics | DAX |
| Data source | Olist E-commerce Dataset |

## Repository structure

```text
Industry-Level-Data-Analytics-Dashboard/
├── README.md
├── Industry-Level Data Analytics Dashboard.pbix
├── Industry-Level Data Analytics Dashboard.pdf
├── Olist_dataset.zip
```

## How to use

1. Download the `.pbix` file from this repository.
2. Open it in **Power BI Desktop**.
3. If needed, reconnect the data source or extract the dataset from `Olist_dataset.zip`.
4. Review the PDF report for a static walkthrough of all dashboard pages.
5. Explore filters, drillthrough pages, and KPI trends in Power BI Desktop.

## Outcomes

This project demonstrates practical skills in:

- Data cleaning and shaping.
- SQL-based analytical modeling.
- Business KPI design.
- Interactive dashboard development.
- Performance-focused reporting design.
- Translating raw data into stakeholder-ready insights.

## Author

**Dinesh Saliyar**  
AI / Data Science / Analytics Projects
