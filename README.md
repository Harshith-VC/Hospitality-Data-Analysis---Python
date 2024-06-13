# AtliQ Hotels Data Analysis Project

## Overview

This project involves a comprehensive data analysis for AtliQ Hotels, a prestigious luxury hotel chain in India operating across Mumbai, Delhi, Hyderabad, and Bangalore. The aim is to delve into their business data from May 2022 to August 2022, uncover insights, and understand the underlying trends affecting their business.

## Project Structure

The project follows a structured approach:
1. **Data Import and Exploration**: Understanding the dataset's structure and content.
2. **Data Cleaning**: Ensuring data quality and consistency.
3. **Data Transformation**: Preparing the data for analysis.
4. **Analysis Insights**: Extracting actionable insights to drive business decisions.

## Datasets

The analysis utilizes the following datasets:
- **Dimension Tables**:
  - `dim_hotel.csv`
  - `dim_room_type.csv`
  - `dim_customer.csv`
- **Fact Tables**:
  - `fact_bookings.csv`
  - `fact_revenue.csv`
  - `fact_expenses.csv`

The dataset contains approximately 135,000 rows of data.

## Files in the Repository

- `AtliQ_Hotels_Data_Analysis.ipynb`: The Jupyter Notebook containing the entire analysis.
- `data/`: A directory containing the CSV files for the dimension and fact tables.
  - `dim_hotel.csv`
  - `dim_room_type.csv`
  - `dim_customer.csv`
  - `fact_bookings.csv`
  - `fact_revenue.csv`
  - `fact_expenses.csv`
  
## Project Execution

The analysis is performed in Python using Pandas within a Jupyter Notebook. Below is a summary of each step:

### 1. Data Import and Exploration

- Importing the datasets using Pandas.
- Understanding the structure and content of each dataset.
- Conducting initial exploratory data analysis (EDA) to get a sense of the data.

### 2. Data Cleaning

- Handling missing values.
- Ensuring consistency in data types.
- Addressing any data quality issues identified during exploration.

### 3. Data Transformation

- Merging dimension and fact tables for comprehensive analysis.
- Creating new features if necessary.
- Preparing the data for analysis by aggregating and transforming as needed.

### 4. Analysis Insights

- Leveraging Pandas' groupby and merge functions to uncover insights.
- Analyzing booking trends, revenue patterns, and expense distributions.
- Identifying key drivers of business performance.
- Providing actionable insights to support strategic decision-making.

## Key Insights

Some of the key insights derived from the analysis include:
- Trends in booking volumes across different cities.
- Revenue performance by hotel and room type.
- Expense patterns and their impact on profitability.
- Customer behavior and preferences.

## Conclusion

This project demonstrates a comprehensive approach to data analysis for a luxury hotel chain. By following the structured approach outlined above, we can derive valuable insights to support strategic business decisions.

