# BI-finanacial-analysis
Interactive Power BI dashboard analyzing sales, revenue, product performance, and business KPIs.
## Table of contents
- [Key Features](#key-features)
- [Tools Used](#tools-used)
- [Objective](#objective)
- [Data Analysis & Dax measusres](#data-analysis--dax-measures)
- [Business Recommendations](#business-recommendations)
- [References](#references)
- [Limitation](#limitations)
- [Key Analysis & Findings](#key-analysis--findings)
-  ## 📑 Table of Contents

- [Key Features](#key-features)
- [Tools Used](#tools-used)
- [Objective](#objective)
- [Business Recommendations](#business-recommendations)
- [References](#references)
- [Limitations](#limitations)
- [Key Analysis & Findings](#key-analysis--findings)



## Project Overview
An interactive Power BI dashboard designed to analyze automotive sales and financial performance. It highlights key metrics such as net sales, total profit, profit margin, and total orders.

## Key Features
- Monthly profit trends
- Net sales by car model
- Profitability by brand
- Orders by customer type
- Monthly payment analysis

## Tools Used
- Microsoft Power BI
- Data Visualization
- KPI Reporting
- Business Intelligence

## Objective
Transform sales and financial data into actionable insights that support better business decisions.

## 📈 Data Analysis & DAX Measures

The dashboard uses DAX (Data Analysis Expressions) to calculate key performance indicators and analyze sales and financial performance.

### Key Measures

**1. Net Sales**
```dax
Net Sales = SUM(Sales[Net Sales])
```

**2. Total Profit**
```dax
Total Profit = SUM(Sales[Profit])
```

**3. Profit Margin**
```dax
Profit Margin = DIVIDE([Total Profit], [Net Sales], 0)
```

**4. Total Orders**
```dax
Total Orders = DISTINCTCOUNT(Sales[Order ID])
```

### Key Analysis & Findings
- Monitored sales, profit, and profit margin.
- Compared net sales across car models.
- Analyzed profitability by vehicle brand.
- Examined customer types and monthly payment trends.
- Used dashboard filters to explore performance across cities and other categories.

- ## 💡 Business Recommendations

Based on the dashboard metrics and sales performance analysis, the following recommendations can help improve business performance:

1. **Focus on High-Performing Car Models:** Prioritize inventory and marketing for models generating the highest net sales while monitoring their profit margins.

2. **Improve Profitability:** Review vehicle pricing, supplier costs, discounts, and operating expenses to identify opportunities to increase profit margins.

3. **Monitor Monthly Performance:** Track monthly sales and profit trends to identify periods of declining performance and adjust marketing or sales strategies accordingly.

4. **Strengthen Customer Engagement:** Analyze individual and business customer purchasing patterns to develop targeted promotions and improve customer retention.

5. **Optimize Payment Plans:** Evaluate payment plan performance and customer payment behavior to support affordable financing options while managing financial risk.

6. **Use Data for Decision-Making:** Regularly monitor KPIs such as net sales, total profit, profit margin, and total orders to measure progress and guide business strategy.

### Expected Business Impact
These recommendations aim to improve sales performance, increase profitability, strengthen customer relationships, and support data-driven business decisions.


## ⚠️ Limitations

- **Data Quality:** The accuracy of the insights depends on the completeness and reliability of the available dataset.
- **Historical Data:** The dashboard focuses on historical performance and does not predict future sales or profitability.
- **Scope of Analysis:** The findings are limited to the available fields, including sales, profit, car models, customer types, and payment plans.
- **External Factors:** Market competition, economic changes, and customer preferences are not fully captured in the analysis.
- **Data Refresh:** The dashboard requires updated data to reflect the latest business performance.

These limitations should be considered when interpreting the results and making business decisions.

## 📚 References

- **Microsoft Power BI Documentation:** https://learn.microsoft.com/en-us/power-bi/
- **DAX Function Reference:** https://learn.microsoft.com/en-us/dax/
- **Power Query Documentation:** https://learn.microsoft.com/en-us/power-query/
- **Microsoft Learn – Data Analytics:** https://learn.microsoft.com/en-us/training/powerplatform/power-bi/

These resources were used as learning references for dashboard development, data transformation, DAX calculations, KPI reporting, and data visualization.


