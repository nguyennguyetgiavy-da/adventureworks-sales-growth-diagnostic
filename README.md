# Sales Growth Diagnostic in AdventureWorks

## Project Overview

A 6-page Power BI executive dashboard analyzing the slowdown in revenue growth within AdventureWorks' Internet Sales business.

The dashboard combines sales, product, customer, and regional performance data to identify which business areas contribute most to declining growth and where management should prioritize improvement efforts.

---

## Business Problem

AdventureWorks experienced a significant deceleration in revenue growth over the analysis period, declining from **+180.3% YoY in FY2019** to **+49.9% in FY2020**, before reaching **-0.6% in FY2021**.

While overall revenue remained stable, the underlying drivers behind the slowdown were unclear. This project investigates whether the problem originates from product performance, customer behavior, or regional market dynamics.

---

## Business Questions

* What factors are contributing to the slowdown in revenue growth?
* Is growth constrained by product performance, customer behavior, or regional markets?
* Which products and categories drive the largest share of revenue?
* How have customer acquisition and retention trends changed over time?
* Which markets present the greatest opportunities and risks for future growth?

---

## Dataset

**Source:** AdventureWorks Internet Sales sample dataset.

The analysis integrates sales, product, customer, geography, and date data through a relational data model built in Power BI.

* **Analysis Period:** FY2018 – FY2021
* **Coverage:** Internet sales transactions across multiple international markets
* **Data Model:** Fact and dimension tables connected through a star-schema structure

---

## Tools Used

* Power BI
* Power Query
* DAX

---

## Key Metrics

* Revenue
* Revenue Growth Rate (YoY)
* Gross Profit Margin
* Active Customers
* New Customers
* Retention Rate
* Revenue per Customer

---

## Key Findings

* Revenue growth decelerated significantly over the analysis period, falling from **+180.3% YoY in FY2019** to **+49.9% in FY2020**, before reaching **-0.6% in FY2021**, indicating that AdventureWorks has entered a mature growth stage.

* Customer retention declined from **45.9% in FY2020** to **27.3% in FY2021**, emerging as the primary driver behind slowing revenue growth.

* Australia remains the largest market, generating **$9.06M (31.6% of total revenue)**, but exhibits signs of market maturity through the slowest revenue growth and declining profit margins among major regions.

* Germany leads revenue growth among major markets (**+59.1% YoY**), while Canada demonstrates the strongest profitability performance with the highest gross margin (**42.0%**) and the largest margin improvement (**+0.6 percentage points YoY**).

* Revenue is highly concentrated within the Bikes category, and the **Top 5 products account for 22.7% of total revenue**, creating dependency on a relatively small set of products.

---

## Business Recommendations

1. Strengthen customer retention initiatives through loyalty programs, repeat-purchase incentives, and post-purchase engagement strategies to address the significant decline in retention rates.

2. Prioritize investment decisions based on both revenue scale and performance metrics, ensuring that growth and profitability opportunities are evaluated within a meaningful business context.

3. Adopt differentiated regional strategies by protecting market share and profitability in mature markets such as Australia, while directing growth investments toward higher-potential markets including Germany and Canada.

4. Reduce revenue concentration risk by expanding the contribution of secondary product lines and strengthening demand across a broader product portfolio.

---

## Dashboard Preview

### Executive Overview

![Executive Overview](images/page1_overview.jpg)

### Sales Overview

![Sales Overview](images/page2_sales_overview.jpg)

### Product Analysis

![Product Analysis](images/page3_product_analysis.jpg)

### Customer Analysis

![Customer Analysis](images/page4_customer_analysis.jpg)

### Regional Analysis

![Regional Analysis](images/page5_regional_analysis.jpg)

### Advanced Analysis

![Advanced Analysis](images/page6_advanced_analysis.jpg)

---

## Technical Highlights

* Built a Power BI data model using fact and dimension tables in a star-schema structure.
* Developed custom DAX measures for customer retention analysis, customer acquisition tracking, and dynamic KPI indicators.
* Applied Key Influencers and Decomposition Tree visuals to support root-cause analysis.
* Implemented bookmarks, page navigation, and conditional formatting to improve dashboard usability.
* Applied materiality thresholds to growth KPIs to prevent small-base effects from distorting business decisions.

---

## Project Files

* AdventureWorks_Report.pdf – Dashboard report for quick viewing.
* Power BI source file (.pbix) available upon request.
