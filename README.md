# Bike Sales Analytics Dashboard – Excel Pivot-Based Business Intelligence Project

## Executive Summary

This project analyzes customer-level sales data to identify demographic and behavioral factors influencing bike purchase decisions.

Using Excel Pivot Tables, Pivot Charts, and interactive slicers, the dataset was transformed into a dynamic reporting dashboard that enables multi-dimensional customer segmentation and purchase trend analysis.

The final output simulates a business intelligence report used for understanding sales drivers and customer targeting strategies.

---

## Business Problem

A retail business wants to understand:

- Which customer segments are most likely to purchase bikes?
- Does income level influence purchase behavior?
- How does commute distance impact buying decisions?
- Which demographic factors correlate with higher purchase rates?

The goal was to structure raw data into a decision-support dashboard capable of answering these questions interactively.

---

## Dataset Overview

The dataset contains structured customer records including:

- Gender
- Age
- Income
- Commute Distance
- Education
- Marital Status
- Region
- Purchased Bike (Yes/No)

Data preparation included:

- Creating age brackets for segmentation
- Grouping commute distance into categorical ranges
- Structuring data for pivot-based aggregation
- Ensuring categorical consistency for slicer functionality

---

# 📊 Final Dashboard

The dashboard consolidates multiple pivot analyses into a unified reporting interface.  
Interactive slicers allow filtering by:

- Marital Status
- Education
- Region

All metrics and charts update dynamically.

<img width="764" height="570" alt="bike-sales-dashboard" src="https://github.com/user-attachments/assets/ce7e0f10-882b-4cc5-ba06-f07ad0c785d4" />

---

## Analytical Approach

### 1. Income vs Purchase Behavior

Objective: Determine whether income levels influence bike purchasing decisions.

Method:
- Pivot Table aggregation using **Average Income**
- Segmented by Gender and Purchase Status

Result:
- Customers who purchased bikes show higher average income levels across both genders.
- Income disparity indicates purchasing power as a strong predictor.

<img width="1140" height="421" alt="income-per-purchase" src="https://github.com/user-attachments/assets/19606d3e-7a15-4659-a731-4a13f9414c87" />

---

### 2. Age-Based Segmentation

Objective: Identify which age group contributes most to total purchases.

Method:
- Grouped age into brackets (Young, Middle Age, Old)
- Aggregated purchase count by age bracket

Result:
- Middle-aged customers represent the highest purchase volume.
- Younger and older groups show comparatively lower buying frequency.

<img width="1279" height="423" alt="purchase-based-on-age" src="https://github.com/user-attachments/assets/641e8b72-0ef5-4ed3-a501-0da465ba3586" />

---

### 3. Commute Distance Impact

Objective: Evaluate whether commute distance influences purchase likelihood.

Method:
- Grouped commute distance into defined ranges
- Calculated purchase counts by distance segment

Result:
- Customers with shorter commute distances show higher purchase rates.
- Purchase frequency declines as commute distance increases.

---

## Technical Implementation

This project demonstrates:

- Multi-dimensional aggregation using Pivot Tables
- Average and Count metrics for behavioral analysis
- Customer segmentation via grouped categories
- Pivot Chart integration for visualization
- Cross-filtering through slicers
- Dashboard layout structuring for executive readability

All visualizations are directly connected to pivot tables, ensuring consistency and dynamic recalculation.

---

## Analytical Capabilities Demonstrated

- Business-driven metric selection
- Behavioral segmentation analysis
- Demographic trend evaluation
- Data grouping and transformation
- Interactive reporting in Excel
- Translating structured data into decision-support visuals
