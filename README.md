# Top Customers

## Objective
The objective of this project is to conduct a preliminary exploration and analysis of Sprocket Central Pty Ltd’s customer datasets, including Customer Demographic, Customer Addresses, and Transactions data. The goal is to identify key areas for data quality improvement, ensuring that the datasets are optimized to support effective analysis and drive business growth. By enhancing data quality, the project aims to enable Sprocket Central Pty Ltd to refine its marketing strategy, better understand customer behavior, and ultimately increase customer engagement and sales.

### Goal
- To get top 1000 Customers
- To know the customer segment, Which customer segment has the highest customer value?

## Data Source
The data is provided by KPMG Virtual Intership.

## Tools & Technologies
- **Excel:** For initial data exploration and preparation.
- **Power BI:** To transform data, create interactive dashboards and visualizations

## Process Overview for Customer Data Quality Assessment and RFM Analysis
### 1. Data Quality Assessment
- **Data Cleaning:**

**Correct Data Types:** Ensure all fields in the datasets have the correct data types (e.g., dates are in date format, numerical fields are numeric, categorical fields are properly labeled).

**Exclude Deceased Customers:** Identify and records of customers are excluded from the dataset to ensure they are not included in the analysis.

### 2.Data Preparation
- **Dataset Integration:**

Integrate Customer Demographics, Customer Addresses, and Transactions data to create a comprehensive dataset that includes all relevant customer information.
- **Data Validation:**

Merged data are cross checked for consistency and correctness to ensure that all customer records align accurately across the different datasets.

### 3.RFM Analysis
- **Calculate RFM Metrics:**

**Recency (R):** Measure the number of days since the customer's last purchase.

**Frequency (F):** Count the total number of purchases made by the customer within a specified period.

**Monetary (M):** Sum the total value of the customer’s purchases during the specified period.

- **Assign RFM Scores:**

Customers Score based on Recency, Frequency, and Monetary values by assigning scores (e.g., 1-5) to each metric, where 1 represents the least favorable and 5 the most favorable behavior.

### 4. Customer Ranking
- **Calculate RFM Score:**

R, F, M scores are combined to calculate an overall RFM score for each customer.
- **Rank Customers:**

Customers are ranked based on their overall RFM score, where the highest rank indicate the most valuable customers.

### 5. Select Top 1000 Customers
- **Filter Top 1000:**

Based on the customer ranks derived from the RFM analysis, the top 1000 customers are selected.
- **Data Export:**

Export the list of the top 1000 customers for further analysis in Power BI and dashboard creation.


### 6. Visualize the data in Power BI

### Visualizations
Now coming on to Visualizations, we have used:

Cards, Filled map, Stacked Column Chart, Clustered Bar Chart, Line Chart and Table

#### 1. Cards

The card shows numbers of male female and unspecified.

#### 2. Filled Map

Map is used to visualize the data state wise.

#### 3. Stacked Column Chart

This chart shows the no of car owners state wise.

#### 4. Clustered Bar Chart

It shows the total property valuation of customers by wealth segment.

#### 5. Line Chart

This chart represents customers age group, and bike related purchase, which age group made maximum bike related purchase in past 3 years

#### 6. Table

A table is used to show 1000 customers details

https://github.com/user-attachments/assets/eced317f-0e70-4eeb-b67e-2b779c213503

### Conclusion from Analysis
Based on the data, here are some insights and findings that can be derived using the visualizations from Power BI:

- 50% of customers are from NSW state.
- State NSW has maximum numbers of car owners.
- Industries like Manufacturing, Financial Services and Health has maximum customers who made purchases related bike services in past 3 years.
- Age group, 40-49 and 50-59 has maximum customers who made purchases related bike services in past 3 years.
- There is not major difference in numbers between Male and Female who made bike related purchase in last 3 years.
