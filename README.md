# Automated Business Performance & Data Quality Reporting System

## Overview
This project demonstrates an end-to-end analytics and reporting automation workflow using SQL and Power BI. The goal is to provide reliable, automated insights into business performance, revenue trends, and data quality.

## Problem Statement
Manual reporting processes are time-consuming, error-prone, and difficult to scale. This project addresses the need for automated, accurate reporting that updates with minimal manual intervention.

## Tools Used
- MySQL (SQL)
- Power BI
- GitHub

## Dataset
The project uses a **public e-commerce transactional dataset** that represents real-world business operations.

### Dataset Characteristics:
- Order-level data with timestamps and status
- Item-level transaction data for revenue calculation
- Payment records for financial validation
- Seller information for performance analysis

## Approach
- Imported raw data into MySQL
- Cleaned and standardized timestamp formats
- Built reusable SQL views for reporting and data quality checks
- Connected Power BI directly to SQL views
- Designed a one-page executive dashboard

## Dashboard Highlights
- Total Revenue, Total Orders, Active Entities
- Monthly Revenue and Order Trends
- Top Entities by Revenue
- Data Quality Alerts (Orders without Items, Orders without Payments)

## Automation Logic
All business logic is implemented in SQL views. As new data is added to the database, views automatically recompute results, and the Power BI dashboard updates upon refresh.

## Key Learnings
- Handling real-world data quality issues
- Building automation-ready SQL reporting layers
- Designing business-focused dashboards

## Screenshots
(See screenshots folder)

