# Sales Data Analysis

An exploratory data analysis project using Python to examine sales performance across regions, product categories, customers, and time.

## Project Overview

The goal of this project is to analyze historical sales data, identify trends, compare business performance, and communicate findings through data analysis and visualizations.

## Tools and Technologies

- **Python** — data analysis
- **Pandas** — data manipulation and aggregation
- **Matplotlib** — data visualization
- **Seaborn** — statistical data visualization
- **Jupyter Notebook** — interactive analysis

## Analysis Performed

- **Regional Sales Analysis:** Compared total sales across regions.
- **Customer Analysis:** Identified the top 10 customers by sales revenue.
- **Product Category Analysis:** Compared sales across Technology, Furniture, and Office Supplies.
- **Monthly Sales Trends:** Examined monthly sales performance and identified the highest- and lowest-sales months.
- **Month-over-Month Changes:** Calculated percentage changes in monthly sales.
- **Data Quality Checks:** Identified missing values in the postal code column for further investigation.

## Key Findings

- **Total Sales:** Approximately $2.26 million across the dataset.
- **Top Region:** West, with approximately $710,219.68 in sales.
- **Top Product Category:** Technology, with approximately $827,455.87 in sales.
- **Lowest-Selling Product Category:** Office Supplies, with approximately $705,422.33 in sales.
- **Highest-Sales Month:** November 2018, with approximately $87,997.64 in sales.
- **Lowest-Sales Month:** February 2015, with approximately $12,588.48 in sales.

These findings describe sales revenue rather than profit. The analysis identifies historical patterns but does not establish the causes behind them.

## Project Structure
sales-analysis/
├── README.md
├── .gitignore
├── data/
│   └── train.csv
└── notebooks/
    └── sales_analysis.ipynb

## How to Run
Dataset: The dataset is included in data/train.csv. Ensure the notebook reads the file from the correct relative path.

### 1. Clone the repository

```bash
git clone https://github.com/amedge821/sales-analysis.git
cd sales-analysis
```

### 2. Install the required libraries

```bash
python3 -m pip install pandas matplotlib seaborn jupyter
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `notebooks/sales_analysis.ipynb` and run the cells from top to bottom.

**Note:** Ensure the dataset is available at the location expected by the notebook. Refer to the dataset source linked in the repository's existing README.

## Limitations

- Missing postal code values were identified but have not yet been resolved.
- The analysis focuses on sales revenue rather than profitability.
- Historical trends do not establish why sales increased or decreased.
- Findings depend on the quality and completeness of the source dataset.

## Future Improvements

- Investigate seasonal sales patterns.
- Examine profit and discount trends if the relevant fields are available.
- Resolve missing postal code values if they are relevant to future analysis.
- Develop an interactive dashboard to explore sales performance.


## Resource

Heres the link in which I've obtained my data from:
https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting?resource=download

