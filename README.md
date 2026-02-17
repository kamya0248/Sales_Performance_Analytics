# Sales Performance Analytics & BI Dashboard

Power Query | Power Pivot | Data Modeling | Strategic Sales Insights

---

## Project Overview

This project analyzes multi-year sales performance data (2019–2021) for a global consumer electronics hardware company specializing in products such as keyboards, mice, and related accessories.

The company operates through:

* Retail stores
* Distributors
* E-commerce platforms
* Direct-to-consumer channels

The objective of this project was to build a Business Intelligence solution using Excel’s Power tools to evaluate performance across customers, markets, divisions, and products, and to generate actionable strategic recommendations.

---

## Business Problem

Despite overall revenue growth, leadership lacked clarity on:

* Which markets are meeting or missing targets
* Which customers drive the majority of revenue
* Which products contribute most to growth
* Which divisions show declining performance
* Whether new product launches are successful
* Revenue concentration risk across SKUs or customers

Management required a centralized analytical dashboard to support data-driven strategic planning.

---

## Tools & Technologies Used

* Microsoft Excel
* Power Query (ETL & Data Transformation)
* Power Pivot (Data Modeling)
* DAX Measures
* Data Model Relationships (Diagram View)
* KPI and Year-over-Year (YoY) Growth Analysis
* Pivot-Based Performance Dashboards

This project was built using a structured BI workflow rather than basic Excel formulas.

---

## Data Engineering Approach (ETL)

Using Power Query:

* Imported and combined multiple datasets
* Cleaned and standardized data formats
* Removed inconsistencies and handled missing values
* Created calculated columns where required
* Prepared structured tables for modeling

The transformation layer ensured clean, analysis-ready data.

---

## Data Modeling

A multi-table data model was created in Power Pivot using defined relationships between:

* Customers
* Markets / Countries
* Divisions
* Products
* Sales fact table

The model was structured to enable:

* Cross-dimensional analysis
* Dynamic filtering
* KPI comparison
* Target vs Actual benchmarking

DAX measures were created for:

* Year-over-Year (YoY) Growth Percentage
* Target Achievement Percentage
* Revenue comparison metrics
* Product ranking

This allowed scalable and dynamic business reporting.

---

## Dashboard & Analysis Modules

### 1. Customer Performance Report

* Multi-year revenue comparison (2019–2021)
* YoY growth tracking
* Identification of high-value and declining customers

### 2. Market Performance vs Target

* Country-level revenue comparison
* Target vs actual analysis
* Percentage target achievement metrics

### 3. Division Sales Performance

* Revenue breakdown by business division
* Growth rate comparison
* Identification of stagnating segments

### 4. Product Performance Analysis

* Top 10 products by revenue
* Bottom 5 products by quantity sold
* Revenue concentration analysis
* New product performance evaluation

### 5. Market Leadership Analysis

* Top 5 countries by revenue contribution

---

## Key Insights

* Revenue growth accelerated significantly in 2021.
* Sales concentration observed among a limited set of high-performing products.
* Certain markets consistently exceed targets, while others underperform.
* A small group of customers contribute disproportionately to total revenue.
* Some divisions show stagnation, indicating strategic reinvestment opportunities.
* New product performance varies, indicating the need for improved launch validation.

---

## Strategic Recommendations

* Reallocate marketing and sales resources toward high-growth markets.
* Reduce inventory exposure for low-performing SKUs.
* Strengthen customer retention strategies for top revenue contributors.
* Improve quarterly target tracking mechanisms.
* Diversify revenue streams to reduce dependency risk.
* Implement product lifecycle review for underperforming launches.

---

## Business Impact (Simulated)

If implemented, expected outcomes may include:

* 8–12% improvement in revenue allocation efficiency
* Reduction in operational waste from low-performing SKUs
* Improved target achievement rate
* Better visibility for executive decision-making

---

## Repository Structure

```
Sales-Performance-Analytics/
│
├── README.md
├── Project_Report.pdf
├── Sales_Analytics_Dashboard.xlsx
├── Data_Model_Architecture.png
├── Screenshots/
```

---
