<img width="1366" height="768" alt="Screenshot (377)" src="https://github.com/user-attachments/assets/391a2937-d970-4eff-9d8b-79d444fa6945" />


# Food Delivery — Restaurant & Food Performance Dashboard

A single-page Power BI dashboard analyzing four months of food delivery order data to answer one question: **which food items and restaurant types perform best?**

## Overview

This project combines four months of raw order data (January–April 2023) with supporting restaurant and food lookup tables into one clean, interactive Power BI report. It's intentionally kept to a single page — the goal was a focused, fast-to-read dashboard rather than a sprawling multi-page report.

## Business Question

What food items and restaurant types are driving the most orders and quantity sold, and how does that change month to month?

## Dataset

| File | Contents |
|---|---|
| `January_23.xlsx` – `April_23.xlsx` | Order-level transactional data: order ID, order date, customer ID, restaurant ID, food item, quantity, delivery status, payment method (~2,750 rows combined) |
| `Other_Data.xlsx` → `Food_Details` | 24 food items mapped to food type (Main Course, Breakfast, etc.) |
| `Other_Data.xlsx` → `Resturant_Details` | 7 restaurants mapped to restaurant type (North Indian, Mughlai, South Indian) |
| `Other_Data.xlsx` → `Customer Details` | 31 customers with membership tier |

## What's on the Dashboard

- **3 KPI cards** — Total Orders, Total Quantity Sold, Total Restaurants
- **Top Food Items** — bar chart of quantity sold by food type
- **Restaurant Type Performance** — bar chart of quantity sold by restaurant type
- **Order Mix** — donut chart showing order share by food category
- **Slicers** — filter the whole page by month and restaurant type

## Tools Used

- **Power BI Desktop** — data modelling and report build
- **Power Query** — combined four monthly files into a single order table and joined it to the food and restaurant lookup tables
- **Excel** — source data

## Skills Demonstrated

- Combining multiple monthly source files into a single fact table (Power Query Append)
- Building a star-schema-style model (orders fact table joined to Food and Restaurant lookup tables)
- Data cleaning (standardizing inconsistent category values)
- Choosing a small, focused set of visuals that directly answer one business question, rather than over-building
- Interactive filtering with slicers

## How to Run

1. Download Power BI Desktop (free) from [powerbi.microsoft.com](https://powerbi.microsoft.com).
2. Open `First_class_transform_data.pbix`.
3. Data is embedded — no connection setup needed.
4. Use the Month and Restaurant Type slicers at the top of the page to filter the dashboard interactively.

## Author

[NAME -Harshit Panchal] | [LINKDIN - www.linkedin.com/in/harshit-panchal-955887205] | [Email- harshitpanchal2277@gmail.com]

Open to Data Analyst / Business Intelligence Analyst roles.
