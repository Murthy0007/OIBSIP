# EDA on Retail Sales Data

## About the Project

This project is part of my Oasis Infobyte Data Analytics internship. I used Python to explore retail sales data and understand sales trends, customer demographics, and product category performance.

## Dataset

The dataset contains 1,000 transaction records and 9 columns, including date, customer ID, gender, age, product category, quantity, price per unit, and total amount.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Work Performed

- Checked the dataset for missing values, duplicate rows, and invalid dates.
- Calculated descriptive statistics for numerical columns.
- Analyzed monthly and quarterly sales trends.
- Explored transaction counts by gender and age group.
- Compared product categories by transaction count, quantity sold, and revenue.
- Created a correlation heatmap to examine relationships between numerical variables.
- Created an additional heatmap to compare average transaction amounts across age groups and product categories.

## Key Findings

- May 2023 had the highest number of monthly transactions.
- Q4 2023 recorded the highest quarterly sales in my analysis.
- Clothing had the highest transaction count and total quantity sold.
- Electronics contributed 34.41% of total revenue and had the highest revenue among the three categories.
- Average transaction amounts varied across age groups and product categories.
- January 2024 had only two transactions, so its monthly sales total needs to be interpreted carefully.

## Limitations

The dataset contains product categories rather than individual product names. Therefore, I could compare category performance but could not identify the top 10 individual products.

The dataset also contains very few transactions for January 2024, which limits comparisons with complete months.

## Conclusion

This project helped me practise data inspection, descriptive statistics, data visualization, and exploratory data analysis using Python. The results provide useful starting points for understanding sales performance and customer purchasing patterns.

## Project Files

- `retail_sales_eda.ipynb` — Jupyter Notebook containing the analysis and visualizations.
- `data/retail_sales_dataset.csv` — Dataset used for the analysis.
- `screenshots/` — Screenshots of important results and charts.
- `requirements.txt` — Python libraries required for the project.
