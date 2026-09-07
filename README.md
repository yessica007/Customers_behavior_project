# Customer Behaviour Analysis

This project analyses customer shopping data to understand purchasing patterns, customer behaviour, subscription trends, and product performance.

## Project Overview

The project uses Python for data cleaning and analysis, SQL for querying the data, and PostgreSQL for storing the processed dataset.

The main objective is to explore customer purchasing behaviour and identify useful trends from the available data.

## Technologies Used

- Python
- Pandas
- SQL
- PostgreSQL
- Jupyter Notebook

## Dataset

The dataset contains information about customer purchases, including:

- Customer details
- Age and gender
- Products and categories
- Purchase amount
- Location
- Season
- Review ratings
- Subscription status
- Shipping type
- Discounts
- Previous purchases
- Payment method
- Purchase frequency

The dataset contains 3,900 customer records and 18 columns.

## Data Preparation

The data was prepared using Python by:

- Checking the dataset for missing values
- Handling missing review ratings
- Renaming columns for easier analysis
- Creating age groups
- Converting purchase frequency into numerical values
- Removing redundant information

## SQL Analysis

SQL was used to analyse different aspects of customer behaviour, including:

- Revenue by gender
- Customer spending patterns
- Product ratings
- Shipping preferences
- Subscriber vs non-subscriber behaviour
- Discount usage
- Customer purchase categories
- Product popularity
- Repeat customers
- Revenue by age group

## PostgreSQL

The processed dataset was stored in a PostgreSQL database for further querying and analysis.

## Project Structure

```text
Customer_Behaviour_Analysis/
│
├── customer_behavior.ipynb
├── customer_shopping_behavior_data.csv
├── queries.sql
└── README.md
