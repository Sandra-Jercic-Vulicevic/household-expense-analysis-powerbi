# Household Expense Analysis (Power BI)

This project was created as the final assignment for the Data Analyst Program at Semos Education.

The dashboard analyzes household spending data from 2021 to 2025 with the goal of understanding spending patterns, identifying potential savings opportunities, and exploring future expense trends.

## Dataset

The dataset contains household expense records from 2021 to 2025.

Each transaction includes information such as:

- Date
- Category
- Subcategory
- Amount
- Flexibility classification
- Controllability classification

The data was cleaned, transformed, and prepared for reporting and analysis in Power BI.

## Expense Classification Logic

To support the optimization analysis, expenses were classified using two additional dimensions:

### Flexibility

Flexibility describes how easily an expense can be adjusted from month to month.

For example, rent and utility bills are considered less flexible, while dining out, entertainment, or food delivery expenses are more flexible and can be reduced more easily.

### Controllability

Controllability describes the level of direct influence a person has over an expense.

Some expenses are difficult to influence in the short term, while others depend primarily on personal spending habits and purchasing decisions.

These classifications were used to identify areas with the greatest realistic savings potential and to support the scenario analysis presented in the dashboard.

## Dashboard Features

The report consists of four pages designed to answer different business questions.

### 1. Expenses Overview

General summary of total expenses, average monthly spending, yearly comparison, and top spending categories.

![Overview](overview.png)

### 2. Cost Analysis & Optimization Potential

Analysis of spending flexibility and controllability, with a focus on identifying areas where costs can realistically be reduced.

![Optimization](optimization.png)

### 3. Savings Simulation

Interactive What-if analysis that allows users to test different spending reduction scenarios and immediately see their impact on total expenses and savings.

![Scenario](scenario-analysis.png)

### 4. Forecast & Future Trends

Monthly spending trend analysis combined with Power BI forecasting to estimate future expenses.

![Forecast](forecast.png)

## Tools Used

- Power BI
- Power Query
- DAX
- Data Modeling
- What-if Parameters
- Forecasting

## Main Findings

- Food is the largest expense category
- A significant share of expenses is controllable
- Food delivery has a noticeable impact on overall food spending
- Small reductions in controllable expenses can generate meaningful savings
- Historical spending shows a relatively stable long-term trend

## What I Learned

Through this project, I improved my skills in:

- Data modeling
- Creating DAX measures
- Building interactive dashboards
- Using What-if parameters for scenario analysis
- Forecasting in Power BI
- Presenting analytical findings to an audience

## Notes

This project was developed as part of my data analytics learning portfolio and represents my end-to-end work in data preparation, modeling, visualization, and analysis.
