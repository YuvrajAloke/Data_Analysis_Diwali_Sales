# Diwali Sales Data Analysis

This project contains the analysis of Diwali sales data, performed using Python and Jupyter Notebook. The analysis helps in understanding sales trends, customer behavior, and performance metrics during the Diwali season.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Data Description](#data-description)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

## Introduction

The objective of this project is to analyze sales data collected during the Diwali season. Using this analysis, we can derive insights into the performance of different products, sales patterns, customer segmentation, and other business metrics. This analysis will help in optimizing marketing strategies, product offerings, and customer targeting during future sales periods.

## Project Structure

The repository consists of the following files:

- `Diwali Sales Data.csv`: This file contains raw sales data, including customer demographics, products sold, sales amounts, and other relevant details.
- `Diwali_Sales_Analysis.ipynb`: This Jupyter notebook contains the Python code used to process and analyze the data. It includes data cleaning, visualization, and insights generation.

## Data Description

The Diwali sales data contains several fields related to the transactions made during the Diwali season. Some of the key columns include:

- **Customer ID**: Unique identifier for each customer.
- **Product Category**: Category of the product sold.
- **Sales Amount**: Total amount of the transaction.
- **Quantity Sold**: Number of items sold in the transaction.
- **Customer Demographics**: Information about the customer, such as age, gender, location, etc.

## Usage

After opening the notebook, you can execute the cells to perform the analysis.

Key sections in the notebook:
- **Data Cleaning**: Handling missing data and correcting data types.
- **Exploratory Data Analysis (EDA)**: Visualizing sales trends, customer demographics, and product categories.
- **Insights Generation**: Summarizing key takeaways from the analysis, such as the best-selling products, highest revenue-generating regions, and customer behavior patterns.

## Results

Some of the key insights derived from the analysis include:
- Maharastra and Karnataka working in IT, Healthcare and Aviation, Married women age group 26-35 yrs from UP are more likely to buy products from Food, Clothing and Electronics category
- The Random Forest prediction model for the Diwali Sales dataset explains 53.5% of the variance in sales, with a Mean Squared Error of 12,713,284. This indicates that the model captures a substantial portion of the relationship between customer demographics (such as age, gender, marital status, and occupation), product categories, and sales amount. The model effectively identifies patterns in customer behavior and purchasing trends, offering useful insights into factors influencing sales. However, while the predictions are fairly accurate, there is still some gap between predicted and actual sales values, suggesting that further feature engineering or tuning could enhance model performance. Overall, this model provides a solid foundation for predicting sales and understanding customer segments.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
