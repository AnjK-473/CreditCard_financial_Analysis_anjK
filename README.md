# CreditCard_financial_Analysis_anjK
A credit card dashboard built with SQL and Power BI that tracks weekly trends and metrics, enabling stakeholders to easily monitor and analyze operational performance.

## Introduction

The Credit Card Financial Analysis and Dashboard project aims to provide comprehensive insights into credit card transactions using Power BI. This project helps stakeholders understand spending patterns, identify trends, and make data-driven decisions to improve financial performance.


## Features

- Overview of credit card transactions.
- Analysis of spending patterns by category, date, and cardholder.
- Key performance indicators (KPIs) such as total spending, average transaction value, and more.
- Interactive dashboards with drill-down capabilities.
- Custom visualizations and charts to highlight important metrics.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have installed Power BI Desktop.
- You have access to the credit card transactions data file (`credit_card.csv`).

## Installation

1. Clone this repository to your local machine:

2. Open the `credit_card.pbix` file in Power BI Desktop.

3. Load the dataset by following the instructions in the `Usage` section.

## Usage

1. **Loading Data:**
    - Open Power BI Desktop.
    - Go to `Home` -> `Get Data` -> `Text/CSV`.
    - Select the `credit_card.csv` file.
    - Load the data into Power BI.

2. **Exploring the Report:**
    - Navigate through different pages of the report to explore various visualizations and insights.
    - Use slicers and filters to interact with the data.

## Data Source

The data used in this project is a CSV file (`credit_card.csv`) containing credit card transaction records. The columns in the dataset include:
- `TransactionID`: Unique identifier for each transaction.
- `Date`: Date of the transaction.
- `Cardholder`: Name or ID of the cardholder.
- `Category`: Category of the transaction (e.g., groceries, entertainment).
- `Amount`: Amount spent in the transaction.
- `Merchant`: Name of the merchant.

## Visualizations

The Power BI report includes the following visualizations:
- **Total Spending Overview**: A card visualization showing the total amount spent.
- **Monthly Spending Trends**: A line chart showing spending trends over time.
- **Spending by Category**: A bar chart displaying the amount spent in each category.
- **Top Merchants**: A table or bar chart showing the top merchants by spending.
- **Transaction Details**: A detailed table with all transaction records.

