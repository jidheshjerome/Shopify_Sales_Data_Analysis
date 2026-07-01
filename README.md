# Shopify_Sales_Data_Analysis
A data analyst project examining 60,000 Shopify orders from 2023 to 2025, focused on evaluating revenue and profit performance across product categories, countries, traffic sources, and payment methods.

# Overview
This project analyses a large scale Shopify sales dataset spanning three years and 17 columns, including product price, revenue, profit, discount percentage, shipping cost, and return status. The goal is to identify which product categories, markets, and channels drive the most value and where opportunities for growth exist.

Data Cleaning (Python): Imported the dataset using pandas, explored structure with df.info() and summary statistics with df.describe(), corrected data types, checked for missing values, and connected the cleaned dataset to MS SQL Server for structured analysis.

Analysis (SQL): Queried the dataset to answer seven core business questions covering revenue by category, profit by traffic source, sales by country, returns by category, top products by profit, monthly revenue trends, and payment method usage.

Visualization (Power BI): Built an interactive dashboard presenting key metrics including average sales, total orders, profit by category, profit by country, revenue by month, and revenue by traffic source.

# Key Findings
Electronics generates the highest revenue, but the gap across all seven categories is narrow, the business has a well-diversified product base

Social Media is the top-performing traffic source for profit, followed closely by Direct and Paid Ads Email trails slightly but remains meaningful

Australia leads all countries in total sales the spread between top and bottom markets is relatively small

Sports and Fashion have the highest return counts, while Home Decor returns the least

Payment method usage is nearly perfectly even across Apple Pay, Cash on Delivery, Credit Card, Debit Card, and PayPal so no single method dominates

Monthly revenue is stable at around 2M per month with a slight dip in February and June 2025
