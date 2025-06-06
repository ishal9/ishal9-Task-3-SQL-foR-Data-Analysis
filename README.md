# Data Analyst Internship Task 3: SQL for Data Analysis

## Overview
This repository contains the SQL queries and outputs for Task 3 of the Data Analyst Internship, focusing on analyzing the `Ecommerce Fashion Store` dataset using SQLite.

## Dataset
- File: `Ecommerce Fashion Store.csv`
- Description: Contains user data from an e-commerce fashion platform, including sales, purchases, and social engagement metrics.

## Queries
The `ecommerce_analysis.sql` file includes queries demonstrating:
1. SELECT, WHERE, ORDER BY: Top sellers in France.
2. INNER JOIN: Users with above-average sales in their country.
3. LEFT JOIN: All users with country user counts.
4. Subquery: Users with above-average social followers.
5. Aggregate Functions: Average sales and total wished products by country.
6. View: Active users with recent logins and activity.
7. Index: Optimized query for high pass rate users.
8. NULL Handling: Products bought with NULLs replaced.


## Challenges and Solutions
- **Large Dataset**: Used a subset for testing due to online tool limitations.
- **Single Table**: Simulated joins using a derived `country_summary` table.
- **NULL Handling**: Used `COALESCE` to manage NULL values in `productsBought`.

## Tools Used
- SQLite (online)
- GitHub for submission
