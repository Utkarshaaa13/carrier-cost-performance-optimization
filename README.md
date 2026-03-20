# Does Higher Cost Mean Better Delivery? Carrier Cost Performance Analysis for a Logistics Company
Analysis of shipping carrier cost and on-time reliability across distance segments to support smarter carrier allocation decisions.

## Business Questions
Do higher-cost carriers actually deliver better? This project tests that assumption using real shipment data and finds it does not always hold.
The analysis answers five business questions:

1. Which carrier has the highest cost and lowest reliability overall?
2. How does UPS performance vary across distance segments?
3. Which carrier is most efficient for short haul shipments (0–300 miles)?
4. How does each carrier perform across every distance bucket?
5. Which carrier should be preferred per distance bucket based on cost and reliability combined?

## Dataset
1,648 delivered shipments across 7 carriers segmented into 4 distance buckets: 0–300, 301–600, 601–900, and 900+ miles.

## Tools Used
 1. Python / Pandas — data cleaning and preparation
 2. Snowflake — cloud data warehouse and SQL analysis
 3. Tableau — interactive dashboard
 4. SQL — CTEs and window functions for carrier performance queries

## Key Findings
1. UPS has the highest average cost but lowest on-time percentage
2. FedEx justifies premium cost in long haul lanes with strong reliability
3. USPS and Amazon Logistics deliver comparable reliability at lower cost
4. Performance varies by distance — aggregate averages hide the real story
5. A distance-aware allocation strategy improves cost efficiency without sacrificing reliability

https://public.tableau.com/app/profile/utkarsha.chandgadkar/viz/CarrierCostandPerformanceOptimizationAnalysis/Story1
