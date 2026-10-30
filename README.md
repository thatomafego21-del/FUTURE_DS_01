# Superstore Sales Performance Analysis

**Author: Thato Mafego**

## Project Overview

For this project, I explored the Superstore sales dataset to understand how the business performed across time, products, categories, and regions. I used Python for data preparation and analysis, then built a Power BI dashboard to present the results in an interactive and easy-to-follow way.

## Objectives

- Track sales and profit over time.
- Identify the products and categories generating the most sales.
- Compare sales, profit, and order activity across regions.
- Summarize performance with business-focused KPIs.
- Present the analysis in a dashboard that users can explore.

## Tools and Technologies

- **Python** for data preparation and analysis
- **pandas** for data cleaning and aggregation
- **Matplotlib** for charts in the notebook
- **Jupyter Notebook** for documenting the analysis
- **Microsoft Power BI** for the interactive dashboard
- **CSV** for the source and prepared datasets

## Dataset

The project uses the Sample Superstore dataset, which contains order-level information such as order and shipping dates, customer segment, geography, product category and sub-category, sales, quantity, discount, and profit.

- Source file: `Task1_dataset/Sample - Superstore.csv`
- Prepared file: `Task1_dataset/Superstores_cleaned.csv`
- Records: 9,994 rows and 21 columns
- Period covered: 2014–2017

## Data Preparation and Analysis

I loaded the source CSV into pandas and reviewed its dimensions, data types, missing values, duplicates, and numeric fields. I converted the order and shipping dates to dates, checked basic data consistency, and saved the prepared data for analysis.

I then grouped the data to examine monthly sales, product and category sales, and regional sales and profit. I also calculated summary KPIs, including total sales, total profit, profit margin, order count, average order value, and units sold.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total sales | $2,297,200.86 |
| Total profit | $286,397.02 |
| Overall profit margin | 12.47% |
| Orders | 5,009 |
| Average sales per order | $458.61 |
| Units sold | 37,873 |

The source dataset is the US Sample Superstore data, so monetary values are shown in USD.

## Dashboard Features and Analysis

The Power BI dashboard (`Task1_dashboard/dashboard.pbix`) is designed to let users explore sales performance through the available report visuals and filters. It presents the analysis across key business views, including:

- Sales and profit KPIs for a quick overview.
- Sales trends over time.
- Product and category performance.
- Regional sales and profit comparisons.
- Interactive filtering to explore selected parts of the data.

## Key Findings

- The dataset records more than $2.29 million in sales and about $286,397 in profit, with an overall profit margin of 12.47%.
- Sales activity can be compared month by month across the 2014–2017 period to identify changes and seasonal patterns.
- Product and category summaries highlight which parts of the range contribute most to revenue.
- Regional comparisons show that revenue and profit should be reviewed together to understand the quality of performance, not sales volume alone.

## Business Recommendations

- Review monthly performance regularly and plan inventory and promotions around observed demand patterns.
- Protect availability and visibility for high-revenue products, while checking their profit contribution before expanding discounts.
- Compare regional profit margins as well as sales when setting regional targets and allocating resources.
- Investigate low-profit or loss-making product and regional combinations to understand the effects of discounts, costs, and product mix.
- Use the dashboard filters to investigate changes by date, product, category, and region before making decisions.

## Project Structure

```text
.
├── Task1_dashboard/
│   └── dashboard.pbix
├── Task1_dataset/
│   ├── Sample - Superstore.csv
│   └── Superstores_cleaned.csv
├── Task1_notebook/
│   └── Task_1.ipynb
└── README.md
```

## Skills

- Data cleaning and quality checks
- Exploratory data analysis
- Date handling and grouping data by time period
- KPI calculation and interpretation
- Product, category, and regional performance analysis
- Python data visualization
- Power BI dashboard development
- Communicating results and recommendations for business audiences
