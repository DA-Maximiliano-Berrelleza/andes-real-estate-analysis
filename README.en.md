# Andes Capital Real Estate | Sales Performance Analysis

[Español](README.md) | English

A case study of sales, revenue, and purchasing behavior during 2023–2024.

## Business context and problem

Transaction data on sales, customers, and properties needed to be brought together to understand business performance over time. I built a Power BI dashboard to identify which property types, sales channels, and customer segments contributed the most revenue, and to examine purchases made after each customer's first recorded purchase.

## My contribution

- **Data validation in Power Query.** Checked data types, missing values, errors, and the uniqueness of customer and property keys.
- **Data modeling in Power BI.** Organized a sales fact table and three dimensions into a star schema with active one-to-many relationships. Built a calendar with a dynamic date range based on sales dates.
- **DAX calculations.** Developed revenue, sales count, average transaction value, and commission metrics, along with year-over-year growth, revenue shares, and calculated columns for cohort analysis. Validated revenue shares with the 2024 filter applied.
- **Communicating results.** Designed three report views with navigation and a year selector. The executive overview presents the main metrics; the sales analysis compares property types, channels, and customer segments; and the cohort matrix shows transactions by month of first purchase and month of sale.

## 2024 results

| Metric | Result |
| --- | ---: |
| Total revenue | 3,164,799,714.00 |
| Number of sales | 4,455 |
| Average transaction value | 710,392.75 |
| Total commissions | 105,891,941.00 |
| Revenue growth compared with 2023 | 11.14% |

## Findings and business implications

- **Casa (House)** accounted for **36.24%** of revenue, the largest share among property types. This supports prioritizing sales of houses.
- **Corredor (Broker)** accounted for **72.89%** of revenue. Before increasing investment in this channel, its costs and conversion should be reviewed.
- The **Primera vez (First-time buyer)** segment accounted for **62.74%** of revenue.
- In 2024, customers in the March 2023 cohort accounted for **482 sales**, while those in the April cohort accounted for **453**. These figures count transactions. Cohorts should be compared over the same follow-up period when evaluating post-sale initiatives.

## Project documentation

The notebook documents data validation, DAX formulas, the data model, and the findings. Calculations and visualizations were developed in Power BI.

[View the notebook and DAX formulas on GitHub](./Andes_Portafolio.ipynb)

[View the Power BI dashboard in PDF](./Andes_Dashboard.pdf)

[View the Colab copy](https://colab.research.google.com/drive/1DL2DzEfTRer2mO-rOrhhOSc5oSGnJ-Jr?usp=sharing)
