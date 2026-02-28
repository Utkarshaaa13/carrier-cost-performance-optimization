# Carrier Cost-Performance Optimization
Shipping carrier performance analysis focused on cost efficiency and distance-based allocation strategy.

## Overview

This project analyzes shipping carrier performance to understand how shipment cost and on-time reliability interact across different operational contexts. 
Using shipment-level data, carriers are evaluated based on average cost and delivery performance, with results segmented by distance to uncover structural differences.
The objective is not simply to rank carriers, but to assess whether a distance-based allocation strategy can improve operational efficiency while maintaining service reliability.

## Problem Statement

Shipping operations must balance two critical objectives: controlling transportation costs and maintaining reliable on-time delivery performance. 
While higher-cost carriers are often assumed to provide better service reliability, this assumption is not always validated through data.
This project aims to evaluate the relationship between shipping cost and on-time performance across multiple carriers. 
By segmenting shipments into defined distance buckets, the analysis seeks to determine whether performance differences are consistent across operational contexts and whether a distance-based carrier allocation strategy can improve overall efficiency without compromising reliability.

## Dataset Overview

The dataset contains shipment-level records used to evaluate carrier cost and on-time performance. Each record includes the carrier name, shipment cost, shipment distance, on-time delivery indicator, and a unique shipment identifier.
For performance analysis, shipments were segmented into four operational distance buckets: 0–300 miles, 301–600 miles, 601–900 miles, and 900+ miles. 
This segmentation allows performance evaluation within meaningful operational contexts rather than relying solely on aggregated averages.
On-time performance was calculated as the average of the binary on-time indicator within each carrier and distance grouping. Cost metrics were evaluated using average shipment cost and supporting aggregated measures.


## Data Preparation

- Filtered delivered shipments to ensure accurate performance measurement  
- Created distance buckets for segmented analysis  
- Calculated carrier-level averages for cost and on-time percentage  
- Computed total spend and cost per mile  
- Structured summary tables for carrier and distance comparisons  

## Analysis Approach

- Compared overall cost vs on-time performance across carriers  
- Identified potential imbalance in UPS positioning  
- Segmented UPS performance by distance to validate structural patterns  
- Benchmarked short-haul (0–300 miles) performance across carriers  
- Built a distance-based performance matrix to evaluate cross-segment trends  
- Combined cost and reliability insights to assess allocation strategy  

## Key Findings

- Higher cost does not consistently correspond to higher reliability  
- UPS demonstrated relatively higher average cost with lower on-time performance  
- Performance varies meaningfully across distance segments  
- Certain carriers outperform others within specific distance ranges  
- Aggregated metrics can mask segment-level inefficiencies  

## Conclusion

1. Carrier performance analysis indicates that higher transportation cost does not consistently translate into superior reliability. Aggregate averages mask structural variation across operational distance segments.

2. UPS demonstrates relatively higher cost without a proportional reliability advantage, suggesting potential misalignment between spend concentration and service performance.

3. FedEx maintains strong reliability in long-haul segments, supporting its use in performance-sensitive lanes where delay risk carries higher operational impact.
   
4. USPS and other cost-efficient carriers deliver comparable reliability in short and mid-range segments, presenting opportunities to reduce average shipment cost without increasing service risk.

5. Overall, the findings support a distance-aware carrier allocation strategy which allows shipment volume to be distributed based on performance strengths, improving cost efficiency while maintaining reliability.

https://public.tableau.com/app/profile/utkarsha.chandgadkar/viz/CarrierCostandPerformanceOptimizationAnalysis/Story1?publish=yes
