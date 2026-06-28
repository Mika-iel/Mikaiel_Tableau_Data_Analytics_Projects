# Sales and Customer Performance Tableau Project

## Dashboard

Interactive Tableau dashboard:

View Dashboards on Tableau Public:

https://public.tableau.com/views/Project101_17826714123150/SalesDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


## Overview

This project focuses on analysing sales and customer performance trends using Tableau. The objective was to compare year-to-year business performance across key metrics, including sales, quantity, profit, customers, and orders.

The project consists of two interactive dashboards:

1. Sales Dashboard – Focused on sales, profit, quantity, and category performance.
2. Customer Dashboard – Focused on customer behaviour, customer distribution, and top-performing customers.

The dashboards analyse company performance between 2021 and 2023 and allow users to interactively filter results by year, products, and locations.

Credits for the dataset and project inspiration go to Data with Baraa


### Tools Used

* Tableau

## Data Preparation & Modelling

The following steps were performed:

* Created the data model within Tableau's data source environment.
* Structured the dataset:
  - Dimension tables: Customers, Locations, Products
  - Fact table: Orders
* Created relationships between tables.
* Checked and corrected column data types.
* Prepared the dataset for dashboard development.


## Dashboard Development Process

## Year Comparison Analysis

### Created a year selection parameter to allow users to compare performance across different years.
* Developed calculated fields to compare the selected year against the previous year.
* Created KPI calculations showing:
  - Current year value
  - Previous year value
  - Percentage difference
* These Calculations were done individually for each KPI

## KPI Development

Key performance indicators were created for:

* Total Sales
* Total Quantity
* Total Profit
* Total Customers
* Sales per Customer
* Total Orders

These KPIs dynamically update based on the selected year and filters.


## Sales Dashboard Development

The Sales Dashboard includes:

* Sales KPI
* Quantity KPI
* Profit KPI
* Sales and Profit by Category horizontal bar chart
* Sales and Profit trends over time
* Weekly sales and profit trend analysis
* Year-over-year comparisons

Additional design features:

* Created calculated fields to highlight minimum and maximum values.
* Used step line charts to improve the visual clarity of trends.
* Added custom tooltips.
* Compared current-year sub-category sales against previous-year performance using background bar charts.
* Added interactive filters for:
  - Year
  - Products
  - Locations


## Customer Dashboard Development

The Customer Dashboard includes:

* Total Customers KPI
* Sales per Customer KPI
* Total Orders KPI
* Customer distribution by number of orders
* Top 10 customers table

Customer behaviour was analysed to identify high-value customers and ordering patterns.


## Dashboard Design & Formatting

The dashboards were enhanced through:

* Custom formatting
* Improved spacing and layout
* Removal of unnecessary gridlines
* Improved titles and labels
* Consistent formatting across visuals
* Interactive filters and tooltips

The final dashboards were designed to provide an intuitive user experience and allow users to explore business performance dynamically.


# Skills Demonstrated

* Tableau dashboard development
* Data modelling
* Fact and dimension table relationships
* Calculated fields
* Parameters
* KPI creation
* Year-over-year analysis
* Data visualisation
* Interactive dashboard design


