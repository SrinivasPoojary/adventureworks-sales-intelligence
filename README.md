# AdventureWorks B2C Sales Intelligence & NEXUS IQ Engine

An end-to-end e-commerce analytics suite and executive scenario companion analyzing ₹29.36M in global transaction volume across 28,000 orders.

---

## Interactive Deliverables

* **Live Web Companion (NEXUS IQ):** [Launch Interactive App](https://srinivaspoojary.github.io/adventureworks-sales-intelligence/)
* **Raw Power BI File (.pbix):** [Download Power BI Model](https://github.com/SrinivasPoojary/adventureworks-sales-intelligence/raw/main/AdventureWorks_Sales_Intelligence.pbix)

---

## Technical Architecture

* **Data Model:** Clean Star Schema centered on `FactInternetSales` with 1-to-many single-direction relationships to `DimCustomer`, `DimProduct`, `DimSalesTerritory`, and an independent contiguous DAX calendar (`DimDate_Clean`).
* **KPI Engineering:** 11 explicit DAX measures covering Total Revenue, Gross Profit, Profit Margin %, YoY Revenue Growth %, and Distinct Order Velocity.
* **Date Bounds:** July 2005 to July 2008 (reflecting inaugural B2C launch and 2007 product catalog expansion).

---

## Key Executive Insights

1. **Category Margin Asymmetry:** Bikes drive 96.4% of top-line revenue (₹2.83 Cr at 41% margin), while Accessories deliver the portfolio's highest margin at 62.6% on 36,000 units sold.
2. **Cross-Sell Opportunity:** A 50% lift in accessory attachment yields an immediate ₹2.19 Lakh expansion in net gross profit.
3. **Apparel Inefficiency:** Clothing represents 9,101 units sold but contributes only ₹1.36 Lakh total gross profit at 40.1% margin.
4. **Geographic Concentration:** Australia (₹2.9M) and the United States (₹2.8M) generate over 58% of global sales.
