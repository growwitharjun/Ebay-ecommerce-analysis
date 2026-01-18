# Ebay-ecommerce-analysis
# E-Commerce Profit Leakage & Customer Risk Analysis

An end-to-end business analysis project to identify why revenue growth does not translate into stable profit in an e-commerce marketplace.

This project focuses on **pricing strategy, customer concentration, and operational performance** and converts raw transaction data into executive-level business insights using Power BI, SQL, Excel, and DAX.

---

## Project Objective

To answer four critical business questions:

1. Where is revenue actually coming from?
2. Which discounts are destroying profitability?
3. Who are the customers funding the business?
4. Are high-value customers being served properly?

---

## Dataset

- 1,200 transactions (2024)
- Multi-category e-commerce platform  
- Categories: Electronics, Fashion, Home & Kitchen, Industrial

Key fields:
order_id, order_date, customer_id, city, state, product, category, quantity, price, discount_percent, revenue, delivery_days, payment_method

---

## KPIs Tracked

- Total Revenue  
- Gross Revenue  
- Discount Loss  
- Average Discount %  
- VIP Revenue Contribution  
- VIP On-Time Delivery Rate  
- Average Delivery Time  

---

## Key Business Findings

- ₹12.99M lost due to discounting (~15% of gross revenue)
- 21–30% discount range caused **52% of total profit leakage**
- Top 20% of customers generate **35% of total revenue**
- VIP customers receive only **38% on-time delivery**
- Industrial category contributes the highest discount-driven losses
- Revenue is geographically concentrated (Maharashtra is the top state)

---

## Dashboard Structure (Power BI)

### Page 1 – Executive Summary
Business size, profit leakage, and revenue dependency on VIP customers

### Page 2 – Revenue & Growth Analysis
Category performance, state-wise revenue, monthly trend, top customers

### Page 3 – Discount & Profit Leakage
Discount bucket analysis and category-level profit loss

### Page 4 – Customer Segmentation & Operations
Dynamic VIP segmentation, revenue concentration, order distribution, delivery performance

---

## Technical Implementation

- Dynamic customer segmentation using DAX ranking
- Discount bucket modeling
- Profit reconstruction (gross vs net revenue)
- KPI system design
- SQL schema & analytical queries
- Business-first dashboard architecture

---

## Business Recommendations

- Reduce 21–30% discount usage by at least 50%
- Implement customer-tier pricing (VIP vs Regular)
- Cap discounts in Industrial category
- Introduce priority delivery SLA for VIP customers
- Track discount loss as a core business KPI

---

## Tools Used

- Power BI (DAX, data modeling, visualization)
- SQL (data modeling & analysis)
- Excel (data preparation)
- GitHub (documentation & versioning)

---

## Author

Arjun  
Business Analytics | Power BI | SQL | Decision Intelligence  

Focus: turning raw data into business leverage.
