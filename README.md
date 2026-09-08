# E-Commerce Customer Journey Analytics

## Project Overview

Analyzed GA4 e-commerce customer behavior to understand the complete customer journey, identify funnel drop-offs, and evaluate engagement and device-level performance.

## Objective

To analyze customer behavior across the e-commerce funnel and identify opportunities to improve conversion and customer engagement.

## Data Source

- Google Analytics 4 (GA4) E-commerce dataset
- BigQuery Public Dataset

## Workflow

Google BigQuery → Python/Pandas → SQL Funnel Analysis → Power BI → Business Insights

## Tools Used

- Google BigQuery
- Google Colab
- Python
- Pandas
- NumPy
- SQL
- Power BI
- DAX
  
## Data Extraction

- Extracted event-level e-commerce data from BigQuery.
- Performed event, time, and device-level analysis using SQL.
- Validated the extracted data before further analysis.

## Data Cleaning & Preparation

- Used Python and Pandas in Google Colab for data cleaning, validation, and preprocessing.
- Prepared the data for customer journey and funnel analysis.

## Customer Analysis

Analyzed:

- Customer funnel progression
- Engagement behavior
- One-time vs returning user behavior
- Session behavior
- Device-level performance

## Funnel Analysis

Analyzed the sequential customer journey:

**Session Start → View Item → Add to Cart → Begin Checkout → Purchase**

## Key Metrics

- **Total Users:** 268.0K
- **Total Sessions:** 355K
- **Product Viewers:** 59.8K
- **Add-to-Cart Users:** 10.9K
- **Checkout Users:** 4.1K
- **Purchasing Users:** 2.3K
- **Overall Conversion:** 0.87%

## Key Insights

- Identified major customer drop-offs across the sequential purchase funnel.
- View Item recorded a 77.60% drop-off from Session Start.
- Add to Cart recorded an 81.78% drop-off from View Item.
- Purchase conversion from Begin Checkout was 56.82%.
- Analyzed one-time vs returning users and session distribution.
- Compared users and overall conversion across mobile, desktop, and tablet devices.

## Power BI Dashboard

Built an interactive Power BI dashboard to visualize:

- Customer journey funnel
- Conversion and drop-off rates
- Daily active users
- Daily purchases
- One-time vs returning users
- Session distribution
- Device-wise users and conversion

![E-Commerce Customer Journey Dashboard](ecommerce-customer-journey-analytics.png)

## Business Insights

- Identify and address major funnel drop-off points.
- Improve product discovery and add-to-cart engagement.
- Analyze device-specific conversion performance.
- Encourage repeat visits and returning-user engagement.
