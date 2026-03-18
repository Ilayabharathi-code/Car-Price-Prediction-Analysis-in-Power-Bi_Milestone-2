# Car Price Analysis Dashboard (Power BI Project)

## Project Overview

This project focuses on analyzing a car price dataset using **Power BI** to uncover insights related to pricing trends, vehicle characteristics, and market patterns.

The workflow includes:

* Data cleaning and transformation
* Data modeling
* DAX calculations
* Interactive dashboard creation
* Insight generation with recommendations

## Objectives

* Analyze factors affecting car prices
* Identify trends based on year, mileage, and engine size
* Compare pricing across brands and fuel types
* Build an interactive dashboard for decision-making

## Dataset Description

The dataset contains information about different cars with the following attributes:

* Brand
* Model
* Year
* Engine Size
* Fuel Type
* Transmission
* Mileage
* Condition
* Price
* 
## Data Cleaning & Transformation

Performed using **Power Query Editor**:

* Removed duplicate records

* Handled missing/null values

* Standardized data types (Year, Price, Mileage)

* Created derived columns:

* Price Category (Low / Medium / High)

* Engine Size Category

## DAX Measures

Key measures created using DAX:

Total Cars = COUNT('Table'[Car ID])

Average Price = AVERAGE('Table'[Price])

Max Price = MAX('Table'[Price])

Min Price = MIN('Table'[Price])

Total Revenue = SUM('Table'[Price])

Avg Mileage = AVERAGE('Table'[Mileage])

## Dashboard Features
# KPI Cards

Total Cars

Average Price

Maximum Price

Minimum Price

# Visualizations

* Price Trend by Year (Line Chart)

* Average Price by Brand (Bar Chart)

* Fuel Type Distribution (Pie Chart)

* Transmission Analysis (Donut Chart)

* Mileage vs Price (Scatter Plot)

* Condition vs Price (Bar Chart)

* Engine Size Impact on Price

# Filters / Slicers

Brand

Fuel Type

Condition

Year

## Key Insights

* Newer cars generally have higher prices

* Cars with lower mileage tend to be more expensive

* Premium brands have significantly higher average prices

* Automatic transmission cars often cost more than manual

* Engine size has a strong impact on pricing

## Recommendations

Focus on low-mileage vehicles for better resale value

Promote high-demand brands to maximize profit

Consider fuel efficiency trends in pricing strategy

Segment customers based on budget (Luxury vs Standard)

## Tools & Technologies

Power BI

Power Query Editor

DAX (Data Analysis Expressions)

## Conclusion
This project demonstrates how raw data can be transformed into meaningful insights using Power BI. The dashboard helps users understand pricing dynamics and supports data-driven decision-making in the automobile domain.
* Standardized data types (Year,
