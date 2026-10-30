# Future Interns Data Analytics Projects

This repository contains three end-to-end data analysis projects completed as part of the Future Interns data analytics internship. The work covers data cleaning, exploratory analysis, KPI development, visualization, and dashboarding with Python and Power BI.

## Projects

### Task 1: Superstore Sales Performance

Analyzes order-level retail sales to understand revenue trends, product and category performance, profitability, and regional results. The notebook cleans the Superstore data, calculates business KPIs, and creates visualizations for monthly sales, leading products, categories, and regions. A Power BI dashboard is included.

**Tools:** Python, pandas, Matplotlib, Jupyter Notebook, Power BI  
**Files:** `Task1_notebook/Task_1.ipynb`, `Task1_dataset/`, `Task1_dashboard/dashboard.pbix`

### Task 2: Telecom Customer Churn

Explores the Telco Customer Churn dataset to profile churn and retention, compare customer segments, and examine how tenure, services, and billing relate to churn. The notebook includes data preparation, summary metrics, and visual analysis.

**Tools:** Python, pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook  
**Files:** `Task_2.ipynb`, `WA_Fn-UseC_-Telco-Customer-Churn.csv`

### Task 3: Bank Marketing Campaign Analysis

Analyzes the UCI Bank Marketing campaign data to measure subscription conversion and compare outcomes by contact channel, month, customer demographics, and previous campaign result. The notebook cleans the data and builds conversion summaries and charts.

**Tools:** Python, pandas, NumPy, Matplotlib, Jupyter Notebook  
**Files:** `Task_3.ipynb`, `bank-full.csv`

## Repository structure

```text
.
├── Task1_dashboard/
│   └── dashboard.pbix
├── Task1_dataset/
│   ├── Sample - Superstore.csv
│   └── Superstores_cleaned.csv
├── Task1_notebook/
│   └── Task_1.ipynb
├── Task_2.ipynb
├── Task_3.ipynb
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── bank-full.csv
├── Bank-Marketing_cleaned.csv
└── Customer_Churn_clean.csv
```

## Getting started

Open the notebooks in Jupyter Notebook or JupyterLab. The Task 1 notebook expects to be run from `Task1_notebook/` and reads `Sample - Superstore.csv` from `Task1_dataset/`; if needed, adjust its input path to `../Task1_dataset/Sample - Superstore.csv`. Tasks 2 and 3 read their source CSV files from the repository root, so run those notebooks with the repository root as the working directory.

Install the commonly used Python packages with:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Open the Power BI dashboard in `Task1_dashboard/dashboard.pbix` with Microsoft Power BI Desktop.

## Data and generated files

The CSV files include source datasets and cleaned analysis outputs. The notebooks may overwrite cleaned CSV outputs when run. The Power BI dashboard is a separate project artifact.

## Skills demonstrated

- Data quality checks and cleaning
- Exploratory data analysis and descriptive statistics
- KPI and conversion-rate calculations
- Trend, category, regional, and customer-segment analysis
- Communicating findings with charts and an interactive Power BI dashboard
