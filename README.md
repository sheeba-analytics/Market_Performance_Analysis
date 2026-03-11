# Market Performance Analysis 

## Project Overview

This project analyzes market performance across four key Latin American countries: Brazil, Chile, Colombia, and Mexico.

The analysis focuses on understanding customer demographics, product performance, and sales trends across a three-year period (2020–2022). The goal is to transform raw business data into a clear and interactive dashboard that supports data-driven decision-making.

## Project Objectives

- Provide a high-level overview of business performance using key KPIs
- Analyze customer demographics by age group, gender, income group, and country
- Identify top-performing and underperforming products
- Understand sales distribution across regions
- Track sales trends over time (yearly, quarterly, monthly)
- Enable detailed product-level analysis through drill-through functionality

## Data Model

The analysis uses a star schema structure:

Sales (Fact Table) → Date (Dimension)
Sales (Fact Table) → Customer (Dimension)

A date table was created to support time-based analysis including Year, Quarter, and Month.

## Dashboard Preview

### Sales Overview
![Sales Overview](screenshots/sales_overview.png)

### Category Performance Analysis
![Category Performance Analysis](screenshots/category_performance_analysis.png)

### Discount Strategy Analysis
![Discount Strategy Analysis](screenshots/discount_strategy_analysis.png)

### Value Score Analysis
![Value Score Analysis](screenshots/value_score_analysis.png)

### Rating Analysis
![Rating Analysis](screenshots/rating_analysis.png)
