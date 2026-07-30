# FastPay Digital Payment Executive Dashboard

A pivot-based Microsoft Excel dashboard designed to provide a high-level overview of business performance for a digital payment and transaction-based business.

This portfolio project transforms transaction-level data from 2021 to 2025 into an interactive one-screen executive report using Excel PivotTables, KPI cards, a Year Slicer, summarized chart data, and Excel charts.


## Dashboard Preview

### Dashboard View 1

![FastPay Executive Dashboard Preview 1](./Screenshot%20Executive%20Dashboard%2001.png)

### Dashboard View 2

![FastPay Executive Dashboard Preview 2](./Screenshot%20Executive%20Dashboard%2002.png)

## Project Objective

The dashboard was created to help business owners and decision-makers quickly understand:

* How much total transaction value is processed
* How much Gross Profit is generated
* Whether the overall Gross Margin is healthy
* How many transactions are completed
* What the average value of each transaction is
* Which business category records the highest transaction activity
* How transaction value changes over multiple years
* Which products and categories contribute the most transaction value

The dashboard is designed as a one-screen executive overview so users can understand the most important business information without scrolling through a long report.

## Dashboard Features

* Interactive Year Slicer
* Six dynamic executive KPI cards
* PivotTable-based calculations and data summaries
* One-screen dashboard layout without vertical scrolling
* Five-year Transaction Value trend
* Monthly Transaction Value and Gross Profit comparison
* Dynamic Top 5 Products by Transaction Value
* Transaction Value analysis by category
* Connected PivotTables and dashboard visuals
* Custom number formatting for large financial values
* Consistent dashboard colors and visual hierarchy
* Dashboard Guide for external users

## Main KPIs

* Total Transaction Value
* Total Gross Profit
* Gross Margin %
* Total Transactions
* Average Transaction Value
* Most Active Category

The Year Slicer updates the connected KPI values and dashboard visuals according to the selected reporting period.

The five-year trend chart provides additional historical context for evaluating the long-term direction of transaction performance.

## Main Dashboard Charts

### 1. Five-Year Transaction Value Trend

Shows the overall movement of Transaction Value from 2021 to 2025 and helps users identify periods of business growth or decline.

### 2. Monthly Transaction Value and Gross Profit

Compares monthly Transaction Value with Gross Profit to help users understand whether higher transaction activity also produces higher profitability.

### 3. Top 5 Products by Transaction Value

Identifies the products that contribute the highest total Transaction Value during the selected reporting period.

### 4. Transaction Value by Category

Shows how total Transaction Value is distributed across the main business categories.

## Excel Functions and Features Used

* PivotTables
* PivotTable Filters
* Slicer and Report Connections
* Excel Tables
* KPI Reference Cells
* Structured Source Data
* Excel Charts
* Combo Column-Line Chart
* Line Chart
* Horizontal Bar Chart
* Category Comparison Chart
* Dynamic Data Labels
* Custom Number Formatting
* Dashboard Shapes and KPI Cards
* Conditional Formatting
* Dashboard Guide Documentation

## Workbook Structure

* **Dashboard Guide** — Explanation of the project, controls, KPIs, charts, and dashboard usage
* **Dashboard** — Main one-screen executive dashboard
* **KPI** — Pivot-based KPI calculations and dashboard reference cells
* **Chart** — PivotTables, summarized chart sources, and supporting calculations
* **Dataset** — Transaction-level source data

## Dataset Overview

* Period: 2021–2025
* Granularity: One row per transaction
* Number of transactions: 2,885
* Number of products: 11
* Number of categories: 5
* Main fields:

  * Transaction Date
  * Service Code
  * Customer ID
  * Category
  * Product
  * Customer
  * COGS
  * Transaction Value
  * Gross Profit
  * Year
  * Month

Customer names are anonymized, and Customer IDs are masked to protect personal information.

## Dataset Preview

The published dataset preview shows the transaction-level structure used to build the PivotTables, KPI calculations, and dashboard charts.

![FastPay Dataset 2021–2025 Preview](./Screenshot%20Dataset%20Fastpay%202021-2025.png)

## Analysis Logic

* `Gross Profit = Transaction Value − COGS`
* `Gross Margin % = Gross Profit ÷ Transaction Value`
* `Average Transaction Value = Total Transaction Value ÷ Total Transactions`
* Total Transactions are calculated by counting transaction-level records
* Most Active Category is identified based on the highest number of transactions
* Product rankings are based on total Transaction Value
* Monthly performance is summarized by Year and Month
* The Year Slicer filters connected PivotTables and dashboard components

## Business Questions Answered

This dashboard helps users answer:

* What is the overall value of transactions processed?
* How much Gross Profit is generated from the transaction activity?
* What is the overall Gross Margin?
* How many transactions are completed?
* What is the average value of each transaction?
* Which category has the highest transaction activity?
* Is Transaction Value increasing or declining over time?
* Which months generate the highest Transaction Value and Gross Profit?
* Which products contribute the highest Transaction Value?
* Which categories contribute the most to overall business activity?

## Business Insights Supported

This dashboard can help users:

* Monitor high-level business performance
* Compare performance across different years
* Identify long-term Transaction Value trends
* Evaluate the relationship between Transaction Value and Gross Profit
* Identify the strongest-performing products
* Understand Transaction Value contribution by category
* Detect periods of increasing or decreasing business activity
* Distinguish transaction volume from financial performance
* Support management discussions using a concise executive view

## Skills Demonstrated

* Excel executive dashboard design
* PivotTable-based reporting
* KPI development
* Transaction data analysis
* Business performance analysis
* Product performance analysis
* Category contribution analysis
* Interactive Slicer implementation
* PivotTable and chart connection management
* One-screen dashboard layout
* Excel chart creation and formatting
* Financial metric calculation
* Data anonymization
* Dashboard documentation
* Business-focused data presentation

## Important Note

This is a portfolio project created to demonstrate Microsoft Excel dashboard, PivotTable, data-analysis, and business-reporting skills.

It should not be interpreted as a real-client financial report or as evidence of actual business performance improvement.

The project does not include VBA, macros, Power Query, SQL, Python, Power BI, external database connections, or automated data refresh.
