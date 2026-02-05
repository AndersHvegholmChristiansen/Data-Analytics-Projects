# Project Background

DKFLOW is a Danish e-commerce company selling multiple product categories across danish regions. The business has experienced steady growth over recent years, accompanied by increasing operational complexity and rising expectations for delivery performance. This project analyzes order flow, delivery outcomes, and product performance using descriptive dashboards to provide management with a clear overview of operational performance.

# Project Goals
- Provide a consolidated overview of order volume and delivery performance over time
- Identify underperforming regions and cities based on delivery targets
- Understand how order flow is distributed across order statuses and product categories
- Assess year over year performance trends across key product categories

# Data Structure Overview
The analysis is based on data representing customers, orders, products, and payments within the e-commerce business. The dataset covers multiple years of transaction activity and supports analysis of performance across time, geography, and product categories. Key data components include:
- Order Data: Order timing, status, and delivery information used to analyze order flow and delivery performance.
- Customer Data: Customer and regional attributes supporting geographic performance analysis.
- Product Data: Product categories and attributes that enables assessing product mix and performance trends.
- Payment Data: Order-level payment values enabling revenue and order value analysis.

Data cleaning and transformations were performed with power Query in Power BI to support consistent aggregation and dashboard-based analysis.

<img width="1573" height="802" alt="image" src="https://github.com/user-attachments/assets/b9b6b0f3-587a-4a25-ab61-ef6862da957a" />
_Screenshot of Data structure_

# Executive Summary
The analysis indicates that DKFLOW operates a broadly stable and scalable order fulfillment network, while also exposing structural performance differences across locations and product categories that impact delivery reliability.
### Highlights
- ~89K total orders processed across the period
- Overall on-time delivery rate of ~93.7 %, remaining within the defined target
- Late delivery rate averages ~7.5 %, but exceeds target levels in several cities
- Delivery performance is uneven across regions and product categories
- Order volume is relatively well distributed across product categories

<img width="1276" height="716" alt="image" src="https://github.com/user-attachments/assets/92a32e16-595b-404d-a0a4-8dcf9709e070" />
_Screenshot of business metrics overview_

### Trends
Order volume and revenue show a sustained upward trend across the period, with growth accelerating into 2017 and stabilising at a higher level in 2018. Delivery performance remains broadly stable over time, but late deliveries fluctuate month to month and tend to increase during high-volume periods, indicating capacity sensitivity. Average order value stays relatively flat despite higher volumes, suggesting that growth is primarily volume-driven rather than driven by changes in pricing or product mix.

- Clear upward trend in both orders and revenue over time
- Growth stabilises at a higher level rather than showing volatility
- Late deliveries increase during peak volume periods
- Average order value remains stable, suggesting that revenue growth is primarily volume-driven.

# Insights Deep Dive

#Delivery Performance and Network Stability
At the overall level, DKFLOW’s delivery performance remains within defined targets, with a stable on-time delivery rate across the observed period. However, this stability masks meaningful variation across the delivery locations. Several cities consistently exceed the late delivery threshold, indicating that performance challenges are geographically concentrated rather than systemic. This suggests that delivery reliability is driven more by local execution conditions than by overall network design.

## Volume Growth and Operational Pressure

Order volume and revenue increase steadily over time, confirming sustained demand growth. While the fulfillment network absorbs this growth without a visible deterioration in overall performance metrics, periods of higher order volume coincide with increases in absolute late deliveries. This pattern points to capacity sensitivity during peak periods, where operational buffers appear to be tighter and less resilient to load fluctuations.

## Product Mix and Structural Complexity

Order volume is relatively well distributed across product categories, reducing dependency on any single category. Despite this balance, year-over-year performance varies across categories, indicating that not all product types scale equally well operationally. Categories with stable or declining growth coexist with faster-growing segments, suggesting differences in fulfillment complexity, handling requirements, or demand patterns that affect delivery outcomes.

## Revenue Dynamics and Growth Quality

Revenue growth closely follows order volume growth, while average order value remains broadly stable. This indicates that growth is primarily driven by increased transaction volume rather than higher value per order. As a result, future revenue expansion may place additional pressure on fulfillment operations unless efficiency improvements or mix changes are introduced.

# Recommendations

