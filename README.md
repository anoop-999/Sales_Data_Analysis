# Sales Data Analysis Using Python

## Project Overview

This project focuses on analyzing sales transaction data to identify revenue trends, product performance, city-wise sales patterns, and customer purchasing behaviour.

Python and Pandas were used to clean, process, and analyze the dataset to generate meaningful business insights.

## Tools and Technologies

- Python
- Pandas
- Jupyter Notebook

## Dataset Description

The dataset contains 120 sales transaction records and 9 columns, including

- Order ID
- Order Date
- Customer ID
- City
- Product
- Category
- Unit Price
- Quantity
- Payment Method

## Data Cleaning and Preparation

- Identified and handled missing values.
- Checked duplicate records and investigated repeated order IDs.
- Standardized text columns.
- Converted order dates into datetime format.
- Excluded records with missing unit prices or quantities from revenue calculations.
- Created a revenue column using unit price and quantity.
- Extracted month information for monthly analysis.

## Analysis Performed

- Overall sales performance
- Category-wise sales analysis
- Product-wise sales analysis
- City-wise sales analysis
- Payment method analysis
- Monthly sales performance
- Customer analysis and segmentation
- Repeat customer analysis
- City and category performance
- Customer segment performance
- Monthly product performance
- City-wise monthly revenue performance

## Key Findings

- Mumbai generated the highest city-wise revenue of 885,770.
- Delhi recorded the highest quantity sold, with 77 units.
- Laptops generated the highest product revenue of 1,302,600.
- Electronics was the highest-performing category, generating 2,052,937.
- July recorded the highest monthly revenue of 617,613.
- Approximately 87.88% of customers were repeat customers.
- Repeat customers contributed approximately 99.43% of total customer revenue.

## Business Recommendations

- Focus on retaining high-value and repeat customers.
- Investigate the factors behind strong revenue performance in Mumbai.
- Maintain sufficient inventory of high-revenue products.
- Investigate monthly revenue fluctuations.
- Develop strategies to encourage repeat purchases from one-time customers.

## Project Structure

```text
Sales_Data_Analysis
│
├── Sales_Data_Analysis.ipynb
├── sales_analysis_dataset.csv
└── README.md
```

## How to Run the Project

1. Download or clone this repository.
2. Install Python and Pandas.
3. Open the Jupyter Notebook.
4. Run the notebook cells to reproduce the analysis.

## Conclusion

This project demonstrates practical skills in data cleaning, data manipulation, exploratory data analysis, and business insight generation using Python and Pandas.