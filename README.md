# Techtronix-Innovation-Project
---
## Overview
---
**Techtronix Innovation** is a leader in the microchip and robotics industry, seeking to address inefficiencies in sales strategies, inventory planning, and market growth. Despite a strong presence across the automotive, consumer electronics, and industrial sectors, the company struggled with demand unpredictability and inconsistent profitability. To support data-driven decision-making, a comprehensive analysis was conducted on a full year’s transaction data, covering sales figures, customer demographics, product details, and financial metrics.

The project analysed company-wide transactional data to assess sales trends, customer behaviour, inventory alignment, profitability, and regional performance. Insights revealed microchips as the top earners, the industrial sector as the most profitable, and the Asia-Pacific region as the most lucrative. High-cost, low-profit products were flagged, while customer and seasonal patterns informed planning. Strategic recommendations focused on optimising production, market-specific pricing, and expanding in high-performing regions.

## Data Dictionary
---
The dataset consists of the following columns:
- `TransactionID:` Unique identifier for each transaction 
- `Date:` Date of the transaction
- `ProductID:` Unique identifier for the product
- `ProductName:` Name of the product
- `ProductCategory:` Category of the product(Microchip, Robotics, Sensor)
- `QuantitySold:` Number of units sold in the transaction
- `UnitPrice:` Sale price per unit
- `TotalSaleAmount:` Total revenue generated from the transaction
- `CustomerID:` Unique identifier for the customer
- `CustomerName:` Name of the customer
- `CustomerSector:` Sector the customer belongs to
- `Country:` Country of the transaction
- `Region:` Region of the transaction
- `ProductionCost:` Cost of producing the units sold
- `Profit:` Profit from the transaction 

## Analysis Goals
---
**Customer Insights** - Explore customer segmentation to uncover purchase patterns, sector-specific preferences, and geographic distribution. Identify the sectors contributing most significantly to sales and profitability

**Sales Performance Analysis** - Identify sales trends across various product categories, sectors, regions, and periods. Highlight the best and worst performers. 

**Profitability Analysis**- Analyse the profitability across different product categories, taking into account sales revenue and production costs. Point out products with high margins and suggest cost reduction strategies.

**Inventory Optimisation**- Evaluate inventory management against sales figures to pinpoint production planning mismatches. Propose methods to better align production with market demands.

**Market expansion opportunities**- Analyse sales and customer data to discover new markets for expansion, emphasising regions and sectors with untapped potential.

## Insights 
---
![Picture2](https://github.com/user-attachments/assets/1b5f60e2-ab99-4990-8032-97ed3b9a9cf8)

**Customer Insights**
- The industrial sector led in revenue generation with $89.3M, while the Automotive sector recorded the lowest at $78.8M.  
- Within the Industrial sector, the USA was the top contributor at $19.2M, whereas Japan contributed the least at $16.2M.  
- In the USA, Microchips had the highest revenue at $7M, while Sensors generated the least at $5.5M.

![Picture1](https://github.com/user-attachments/assets/0d6a4dea-f0b6-4f57-8205-889bc00d9fc5)
  
**Sales Insights**
- Techtronix invested $4M in production and sold 501K units in 2023, generating a total revenue of $252M and a profit of $53M.  
- The lowest monthly revenue was recorded in May at $18.7M, while April had the highest at $23.2M.
-  Regionally, the USA led in revenue with $52.1M, whereas South Korea generated the least at $49.2M.
-  Analysing production costs versus profits per product, product_1100 had the highest production cost at $48K but yielded only $0.33M in profit. In contrast, product_1315 had a lower production cost of $35K yet delivered a higher profit of $0.68M. This suggests a strategic shift toward products with higher profitability and lower production costs, as seen in the cases of product_1100 and product_1403.
-  Among product categories, Microchips contributed the highest revenue at $97M (38.6% of total revenue), followed by Sensors at $76M (30%).

![Picture3](https://github.com/user-attachments/assets/503a8f4d-0136-4d38-ba86-79c97eff1033)

**Inventory Management and Profitability Insights**
- Sales analysis by product category shows that Microchips had high sales in Q1 at 51.43K units but yielded a relatively low profit of $4.7K. Similarly, Robotics recorded 51.01K units sold in Q1 but only $3.8K in profit. However, Robotics in Q2 showed an improved profit of $5.8K at 49.19K sales, increasing further in Q3 to $6.5K with 49.42K units sold.
- Revenue distribution across customer sectors was relatively balanced, with Industrial ($89M), Consumer Electronics ($84M), and Automotive ($79M). However, Industrial led in profit at $20M, while Automotive had the lowest at $17M. Additionally, production costs showed a slight decline, from $1.3K in the Industrial sector to $1.2K in Automotive.
- A profit margin analysis revealed that Q3 had the highest average margin at 23%, whereas Q1 had the lowest at 19%. Some products even recorded negative profit margins, which is a concern for overall profitability.  

![Picture4](https://github.com/user-attachments/assets/0af45d55-cdde-4d7b-b292-552016e562fe)

**Expansion Insights**
- Microchips had the highest production cost and sales volume at $1.53M and 0.19M units, while Sensors had the lowest at $1.21M and 0.15M units.
- The Asia-Pacific region generated the highest total profit at $18.9M, whereas North America recorded the lowest at $16.2M.
- Across regions, Microchips emerged as the top revenue-generating product category in Europe, Asia-Pacific, and North America.
- Customer_25 was the top revenue-generating customer, contributing $3.44M, and should be recognised for their business impact.
- The USA recorded the highest number of transactions (2,040), total profit ($12.28M), and total revenue ($52.15M). Notably, while China ranked second in transactions, South Korea, despite having the lowest number of transactions, achieved the second-highest total profit at $11.06 M.

## Recommendation 
---
I recommended that Techtronix focus on high-margin products like Microchips and profitable Sensors while minimising investment in low-profit lines. Reducing production inefficiencies and adopting market-specific pricing, especially in regions like South Korea, can boost revenue. Emphasis should be placed on the Industrial sector and Q3 peak seasons, while improving performance in underperforming areas like North America. Retaining high-value customers through loyalty programs and improving profitability in high-volume regions like China are also key.

## Conclusion 
---
By aligning production with demand, leveraging regional strengths, and refining pricing and customer strategies, Techtronix can enhance profitability and position itself for sustainable market expansion.


