# Coffee Shop Dashboard

## Overview
The **Coffee Shop Dashboard** is an interactive Excel dashboard designed to analyze sales transactions from a coffee shop dataset. This project aims to provide insights into sales performance, product trends, and operational recommendations based on historical data.

## Objectives
The project was structured around three key objectives:

### Objective 1: Data Preparation
- Explored the coffee shop dataset to understand its structure and contents.
- Conducted data quality assurance (QA) and profiling.
- Added calculated fields:
  - **Revenue**: Calculated as `price * quantity`.
  - **Month**: Extracted and formatted as text (e.g., "Jan", "Feb").
  - **Day of Week**: Extracted and formatted as text (e.g., "Sun", "Mon").
  - **Hour**: Extracted from the transaction time.

### Objective 2: Data Exploration with Pivot Tables
- Created several PivotTables to analyze the data:
  - Revenue by month.
  - Number of transactions by day of week.
  - Number of transactions by hour of day.
  - Number of transactions by product category (sorted in descending order).
  - Number of transactions and revenue by product type (Top 15 sorted by transactions).

### Objective 3: Dynamic Dashboard Creation
- Developed Pivot Charts to visualize key metrics:
  - Line chart for revenue by month.
  - Column charts for transactions by day of week and hour of day.
  - Bar chart for transactions by product category.
- Assembled charts into a cohesive dashboard layout.
- Added a slicer for store location to enable dynamic filtering across all PivotTables.
- Polished the dashboard with formatting adjustments and removed unnecessary gridlines for clarity.

## Insights and Recommendations

### Astoria Branch
- **Highest Revenue**: Month 6 with revenue of $55,083.
- **Average Transactions**:
  - Highest: Thursdays with an average of 7,427.
  - Lowest: Saturdays with an average of 6,942.
- **Average Transactions by Hour**:
  - Highest: 10th hour with a count of 5,291.
  - Lowest: 14th hour with a count of 3,319.
- **Transactions by Category**:
  - Highest: Coffee with a count of 20,025.
  - Lowest: Packed Chocolate with a count of 110.
- **Top 3 Products**:
  1. Brewed Chai Tea: 6,293 transactions, $27,428 revenue.
  2. Gourmet Brewed Coffee: 6,053 transactions, $23,823 revenue.
  3. Barista Espresso: 4,930 transactions, $27,935 revenue.

### Hell's Kitchen Branch
- **Highest Revenue**: Month 6 with revenue of $56,957.
- **Average Transactions**:
  - Highest: Fridays with a count of 7,489.
  - Lowest: Saturdays with a count of 6,486.
- **Average Transactions by Hour**:
  - Highest: 10th hour with a count of 6,957.
  - Lowest: 20th hour with a count of 528.
- **Transactions by Category**:
  - Highest: Coffee with a count of 20,187.
  - Lowest: Packed Chocolate with a count of 197.
- **Top 3 Products**:
  1. Barista Espresso: 6,153 transactions, $32,420 revenue.
  2. Brewed Chai Tea: 5,824 transactions, $25,645 revenue.
  3. Gourmet Brewed Coffee: 5,642 transactions, $23,010 revenue.

### Lower Manhattan Branch
- **Highest Revenue**: Month 6 with revenue of $54,446.
- **Average Transactions**:
  - Highest: Mondays with a count of 7,136.
  - Lowest: Sundays with a count of 6,679.
- **Average Transactions by Hour**:
  - Highest: 10th hour with a count of 6,279.
  - Lowest: 20th hour with a count of 75.
- **Transactions by Category**:
  - Highest: Coffee with a count of 18,204.
  - Lowest: Packed Chocolate with a count of 349.
- **Top 3 Products**:
  1. Barista Espresso: 5,320 transactions, $31,051 revenue.
  2. Gourmet Brewed Coffee: 5,217 transactions, $23,201 revenue.
  3. Brewed Chai Tea: 5,066 transactions, $24,009 revenue.

### Recommendations
To enhance operations at Maven Roasters, consider:
- **Astoria Branch**: Focus marketing efforts on Thursdays and increase staff during peak hours in the 10th hour.
- **Hell's Kitchen Branch**: Optimize product placement for coffee and consider promotions on Fridays to maximize revenue.
- **Lower Manhattan Branch**: Investigate sales strategies to boost Sunday transactions and maintain product diversity to appeal to all customer preferences.

## Getting Started
To view the dashboard, download the Excel file from this repository and enable macros if prompted. 

## Technologies Used
- Microsoft Excel
- PivotTables
- PivotCharts
- Data Analysis Techniques

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgements
Maven Analytics
