# EDA on Retail Sales Data

## Project Overview

This project explores retail sales data to identify sales trends, product category performance, and customer purchasing patterns.

The objective is to clean and analyze the dataset using Python and visualize key business insights.

## Objectives

- Inspect and prepare the dataset.
- Analyze sales performance by product category.
- Explore monthly sales trends.
- Compare sales by gender and age group.
- Identify key business insights using data visualizations.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The dataset contains 1,000 retail transactions and the following information:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

## Key Findings

- Total revenue: **456,000**.
- Number of transactions: **1,000**.
- Average transaction amount: **456**.
- Electronics generated the highest category revenue: **156,905**.
- May 2023 was the strongest month, with sales of **53,150**.
- Sales were almost evenly distributed between female and male customers.
- Customers aged 46 and above represented the largest age group by transaction count.

**Note:** January 2024 contains only two transactions in this dataset, so it should not be compared directly with complete months.

## Project Structure

```text
DataAnalytics-L1-EDARetailSales/
├── data/
│   └── retail_sales_dataset.csv
├── outputs/
│   ├── monthly_sales.png
│   ├── sales_by_category.csv
│   ├── sales_by_category.png
│   ├── sales_by_gender.png
│   ├── sales_by_gender.csv
│   ├── sales_by_gender_category.csv
│   ├── sales_by_gender_category.png
│   └── transactions_by_age_group.png
├── EDA_Retail_Sales.ipynb
└── README.md
```

## How to Run

1. Install Python and Jupyter Notebook.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Open `EDA_Retail_Sales.ipynb` in Jupyter Notebook.
4. Run the cells in order.

## Conclusion

This exploratory data analysis highlights differences in category performance, monthly sales, and customer purchasing behavior. The findings demonstrate how Python visualization and data analysis tools can support retail business decisions.

## Author

Sara Tahiri

## Internship

Oasis Infobyte — Data Analytics Internship
