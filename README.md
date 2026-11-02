# Visualizing Business Performance with Matplotlib

## Project Title
Visualizing Business Performance with Matplotlib

## Business Problem
A small business owner needed a clear, structured visual report to understand the company's overall operational trajectory over a six-month period. Without a visual representation, raw numbers make it difficult to quickly identify growth trends, customer patterns, and product sales performance.

## Project Objectives
* Transform six months of business numerical data into meaningful visualizations.
* Build a single structured figure containing three distinct charts using Matplotlib subplots (`plt.subplots()`).
* Analyze monthly revenue trends, customer growth, and individual product sales.
* Communicate data-supported observations clearly and professionally.

## Dataset Description
The analysis is based on six months of operational records containing the following variables:
* **Months**: Reporting period from Month 1 through Month 6.
* **Revenue**: Monthly business revenue measured in Nigerian Naira (N).
* **Customers**: Total number of unique customers recorded each month.
* **Product A**: Monthly sales units recorded for Product A.
* **Product B**: Monthly sales units recorded for Product B.

## Tools and Libraries Used
* **Python**: Core programming language.
* **Jupyter Notebook / Google Colab**: Interactive environment used for writing and executing code.
* **Matplotlib**: Python library utilized for data visualization and building subplots.

## Summary of the Charts Created
The project utilizes a 2x2 grid layout via `plt.subplots()` to present three synchronized visual reports:
1. **Monthly Revenue Trend**: A line chart mapping financial growth over the six months.
2. **Monthly Customer Growth**: A line chart tracking the expansion of the customer base.
3. **Product Performance Comparison**: A multi-series line chart comparing the monthly unit sales of Product A versus Product B.

## Key Observations
* **Upward Revenue Trajectory**: Revenue grew steadily from N150,000 in Month 1 to a peak of N240,000 in Month 6.
* **Correlated Dips**: A minor contraction occurred in Month 3 (revenue dropping to N158,000), which aligned with a brief dip in monthly customer acquisition.
* **Customer Alignment**: Customer growth closely mirrored the revenue trajectory, expanding from 80 to 140 active customers.
* **Product Dominance**: Product A consistently outperformed Product B, finishing the period with 75 units sold compared to Product B's 58 units.

## Instructions for Running the Notebook
1. Ensure you have **Python** and **Jupyter Notebook** installed on your system.
2. Install the required visualization package by running the following command in your terminal or notebook cell:
   ```bash
   %pip install matplotlib
