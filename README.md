# Bike Sales Analysis Dashboard – Customer Segmentation & Purchase Trends

## Executive Summary

This project analyzes customer-level sales data to understand the factors influencing bike purchase decisions.

Using Excel Pivot Tables, Pivot Charts, and slicers, the dataset was transformed into an interactive dashboard that enables segmentation by demographics such as income, age, and commute distance.

The goal is to identify patterns in customer behavior that can support more effective targeting and decision-making.

---

## Business Problem

A retail business wants to understand:

- Which customer segments are most likely to purchase bikes?  
- Does income level influence purchase behavior?  
- How does commute distance impact buying decisions?  
- Which demographic factors correlate with higher purchase rates?  

The objective is to turn raw customer data into a structured view that supports these questions.

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

- creating age brackets for segmentation  
- grouping commute distance into categorical ranges  
- structuring data for pivot-based aggregation  
- ensuring consistent categories for filtering and analysis  

---

## 📊 Final Dashboard

The dashboard consolidates multiple pivot-based analyses into a single view.

It includes slicers for:
- Marital Status  
- Education  
- Region  

All charts update dynamically based on selections, allowing quick comparison across different customer segments.

<img width="764" height="570" alt="bike-sales-dashboard" src="https://github.com/user-attachments/assets/ce7e0f10-882b-4cc5-ba06-f07ad0c785d4" />

---

## Analytical Approach

### 1. Income vs Purchase Behavior

**Objective:**  
Determine whether income influences bike purchasing decisions.

**Method:**  
- Used Pivot Tables to calculate average income  
- Compared customers based on purchase status and gender  

**Result:**  
Customers who purchased bikes have higher average income across both genders.

**Interpretation:**  
Higher income is associated with a greater likelihood of purchase, making it a useful factor for targeting and pricing strategies.

<img width="1140" height="421" alt="income-per-purchase" src="https://github.com/user-attachments/assets/19606d3e-7a15-4659-a731-4a13f9414c87" />

---

### 2. Age-Based Segmentation

**Objective:**  
Identify which age groups contribute most to bike purchases.

**Method:**  
- Grouped customers into age brackets (Young, Middle Age, Old)  
- Aggregated purchase counts by age group  

**Result:**  
Middle-aged customers account for the highest number of purchases.

**Interpretation:**  
This segment represents the most active buyer group and can be prioritized in marketing efforts.

<img width="1279" height="423" alt="purchase-based-on-age" src="https://github.com/user-attachments/assets/641e8b72-0ef5-4ed3-a501-0da465ba3586" />

---

### 3. Commute Distance Impact

**Objective:**  
Evaluate whether commute distance affects purchase behavior.

**Method:**  
- Grouped commute distance into defined ranges  
- Calculated purchase counts for each segment  

**Result:**  
Customers with shorter commute distances show higher purchase rates.

**Interpretation:**  
Shorter commute distances may indicate lifestyle patterns that align more closely with bike usage.

---

## Technical Implementation

This project demonstrates:

- Pivot Table-based aggregation across multiple dimensions  
- Use of average and count metrics for behavioral analysis  
- Data grouping for categorical segmentation  
- Integration of Pivot Charts for visualization  
- Use of slicers for dynamic filtering  
- Dashboard layout design for clarity and usability  

All visualizations are directly connected to pivot tables, ensuring consistent and dynamic updates.

---

## Key Takeaways

- Income is a strong indicator of purchase likelihood  
- Middle-aged customers represent the most active buyer group  
- Shorter commute distances are associated with higher purchase rates  

These insights can be used to improve customer targeting and support more effective marketing decisions.
