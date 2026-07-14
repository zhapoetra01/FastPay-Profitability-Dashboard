# FastPay Digital Payment Profitability Dashboard

A formula-driven Microsoft Excel dashboard designed to analyze the profitability of a digital payment and transaction-based business.

This portfolio project transforms transaction-level data from 2021 to 2025 into an interactive profitability report using Excel formulas, helper tables, a Form Control Combo Box, dynamic rankings, and regular Excel charts.

## Project Objective

The dashboard was created to help business users understand:

* How much transaction value is processed
* How much of that value is used to cover transaction costs
* How much Gross Profit remains
* How Gross Margin changes throughout the year
* Which products generate the highest total Gross Profit
* Which products generate the highest Profit per Transaction

The dashboard focuses on the characteristics of a high-volume, low-margin digital payment business.

## Dashboard Features

* Year selection using a Form Control Combo Box
* Dynamic KPI cards
* Formula-driven calculations without using Pivot Tables as the main dashboard engine
* Monthly Gross Profit and Profit per Transaction trend
* Monthly Gross Margin trend
* Transaction Value to Gross Profit Waterfall chart
* Dynamic Top 5 Products by Gross Profit
* Dynamic Top 5 Products by Profit per Transaction
* Dynamic chart titles based on the selected year
* Dashboard Guide for external users

## Main KPIs

* Total Transaction Value
* Total COGS
* Total Gross Profit
* Gross Margin %
* Profit per Transaction
* Total Transactions

All KPI values and charts update automatically when the selected year changes.

## Excel Functions and Features Used

* `SUMIFS`
* `COUNTIFS`
* `IFERROR`
* `RANK.EQ`
* `XLOOKUP`
* `CONCAT`
* `INDEX`
* Structured References
* Excel Tables
* Form Control Combo Box
* Helper Tables
* Dynamic Chart Titles
* Secondary Axis
* Custom Number Formatting
* Waterfall Chart
* Horizontal Bar Charts
* Combo Column-Line Chart

## Workbook Structure

* **Desain** — Main profitability dashboard
* **Dashboard Guide** — Explanation of dashboard controls, KPIs, and charts
* **Dataset** — Transaction-level source data
* **KPI** — KPI calculations and Combo Box control cells
* **Calculation** — Helper tables, monthly calculations, rankings, and chart sources

## Dataset Overview

* Period: 2021–2025
* Granularity: One row per transaction
* Number of transactions: 2,885
* Main fields:

  * Transaction Date
  * Customer
  * Customer ID
  * Category
  * Product
  * Service Code
  * COGS
  * Transaction Value
  * Gross Profit
  * Year
  * Month

Customer names are anonymized, and Customer IDs are masked.

## Analysis Logic

* `Gross Profit = Transaction Value − COGS`
* `Gross Margin % = Gross Profit ÷ Transaction Value`
* `Profit per Transaction = Gross Profit ÷ Number of Transactions`
* Monthly metrics are calculated using the selected year and month
* Product rankings are calculated using `RANK.EQ`
* Product names and values for the Top 5 charts are returned using `XLOOKUP`

## Business Insights Supported

This dashboard can help users:

* Monitor profitability by year
* Compare monthly Gross Profit performance
* Track changes in Gross Margin
* Understand the relationship between Transaction Value, COGS, and Gross Profit
* Identify products with the highest total profit contribution
* Identify products with the highest profit generated per transaction
* Distinguish transaction volume from transaction profitability

## Skills Demonstrated

* Excel dashboard design
* Formula-driven reporting
* KPI development
* Transaction data analysis
* Profitability analysis
* Product performance analysis
* Dynamic Top 5 ranking
* Helper-table development
* Excel chart creation and formatting
* Dashboard documentation

## Important Note

This is a portfolio project created to demonstrate Excel dashboard and business-reporting skills. It should not be interpreted as a real-client financial report or as evidence of actual business performance improvement.

The project does not include VBA, macros, Power Query, SQL, Python, Power BI, external database connections, or automated data refresh.
