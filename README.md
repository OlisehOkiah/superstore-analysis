# Superstore Data Analysis

## Overview
This project involves a comprehensive analysis of a Superstore dataset, containing detailed records of sales transactions. The primary objective is to extract insights into sales, profit trends, and customer behaviors, enabling data-driven decision-making for business optimization.

---

## Dataset Information
- **File Name**: `Sample - Superstore.csv`
- **Number of Rows**: 9,994
- **Number of Columns**: 21

### Key Columns:
- `Order Date`, `Ship Date`: Transaction and shipment dates.
- `Sales`, `Profit`: Financial metrics for each transaction.
- `Category`, `Sub-Category`: Product classifications.
- `Region`, `City`: Geographical data.
- `Quantity`, `Discount`: Order details.
- `Customer Name`, `Segment`: Customer-related details.

---

## Steps of Analysis

### 1. Data Exploration
- Loaded and previewed the dataset to understand its structure.
- Checked for missing values and dataset dimensions.
- Converted `Order Date` and `Ship Date` columns to datetime format.

### 2. Key Insights and Visualizations

#### A. **Top Products by Quantity**
- Identified the most frequently purchased products:
  - Staples
  - Staple Envelopes
  - Easy-Staple Paper

#### B. **Sales and Profit by Category**
- Compared total sales and profit across three categories:
  - **Technology**: Highest sales and profit.
  - **Furniture**: Moderate profit with high sales.
  - **Office Supplies**: Consistent contributor to profit.
- Created a bar chart to visualize the differences.

#### C. **Profit Analysis by Sub-Category**
- **Highest Profit Sub-Category**: Copiers.
- **Lowest Profit Sub-Category**: Tables (notable losses).
- Used a horizontal bar chart for comparison.

#### D. **Trend Analysis**
- Monthly trends in sales and profit were visualized using a line chart.

#### E. **Top Customers by Revenue**
- Identified the top 10 customers contributing the highest revenue:
  - Sean Miller
  - Tamara Chand
  - Raymond Buch

#### F. **Regional Contribution**
- Examined sales and profit contributions by region:
  - West region was the most profitable.
  - South region had the least contribution.
- Stacked bar chart provided an easy comparison.

#### G. **Segment-wise Profit**
- The Consumer segment generated the highest profit, followed by Corporate and Home Office.

#### H. **Delivery Time Analysis**
- Calculated average delivery time by shipping mode:
  - Same Day: Fastest (0.04 days on average).
  - Standard Class: Slowest (5.0 days).

#### I. **Discount vs. Profit Correlation**
- Visualized the impact of discounts on profit using a scatter plot.

#### J. **Product-Specific Insights**
- **Top Products by Sales Revenue**: Canon imageCLASS 2200 Advanced Copier.
- **Top Products by Profit**: Same as above.
- **Average Quantity by Sub-Category**: Visualized with bar charts.

---

## Tools and Libraries

### Programming Language
- Python

### Libraries
- **Pandas**: For data manipulation and analysis.
- **Matplotlib**: For creating visualizations.
- **Seaborn**: For advanced statistical plotting.
- **Datetime**: For date-related operations.

---

## File Structure
```
|-- data
|   |-- Sample - Superstore.csv  # Dataset
|
|-- notebooks
|   |-- superstore.ipynb           # Python notebook for analysis
|
|-- README.md                    # Project description
```

