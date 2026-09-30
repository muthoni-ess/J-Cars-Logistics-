# JCars_Logistics
A power bi solution for Jcars Logistics Company which imports,sells and delivers vehicles to customers across different regions in Kenya.
To help management track business growth and perfomance,this project turns transactional data into actionable executive insights on revenue, sales volume and profitability.

## Table of Contents
- Project Overview
- Key Features & Metrics
- Data Architecture & Modeling
- Business Insights
- Challenges faced
- Assumptions
- Conclusion
  
## Project Overview
The primary objective of this dashboard is to help management evaluate overall performance, track sales by region and vehicle make and identify drivers behind profitability.

## Key Features & Metrics
- Total Revenue: KSh 1.35 Billion
- Total Units Sold: 466 vehicle units across 9 distinct models
- Gross Profit & Margin: KSh 515.45 Million operating profit at a consistent 30% gross margin
- DAX Measures: Custom calculations using core functions (SUM, DIVIDE, CALCULATE, DISTINCTCOUNT)

 ## Data Architecture & Modeling
- Star Schema: Structured with a central Fact table linked to dimension tables (Customer, Region, Sales Rep)
- Power Query: Data cleaned, standardized and transformed prior to modeling

## Business Insights
- Regional Dominance: The Rift Valley and Western regions lead overall sales volume.
- Top Models: Specific models like the BMW 320i and Toyota Axio account for significant sales representative success.
- Growth Opportunities: Sales in major urban hubs like Nairobi lag behind rural regional hubs, pointing to potential market expansion.
## Challenges Faced
- Regional Performance Disparity-Strong concentration of sales in Rift Valley and Western highlights an underperformance or untapped potential in key major urban hubs like Nairobi.
- Data Quality & Tracking Issues-The presence of an "Unknown" region entry suggests data entry gaps or unassigned sales locations in the source data.  
- ​Revenue heavily dependant on a single dominant vehicle eg.Toyota drive a significant portion of representative sales, while other brands along the bottom chart eg Mazda, Mercedes-Benz, Mitsubishi,Honda,Subaru, show flat or very low individual counts in comparison.
- Dependence on Specific Sales Representatives: Volume is heavily dependent on a few key sales representatives (e.g., Aisha Mohamed and Grace Njeri)therefore posing potential operational risks if staff turnover occurs.  

## ​Assumptions
- Data Completeness: The dataset represents the entire operational transaction history within the defined reporting period (no unrecorded offline transactions). 
​- Region Categorization: Sales are assigned to regions based on customer location or vehicle delivery points rather than dealership headquarters. 
- Product Classification: Each unit sold corresponds to a single vehicle unit across the listed makes and models.
​- Uniform Market Availability: Vehicle inventory and model availability availability were evenly distributed across regions during the reporting period.
  
## Conclusion
​J Cars and Logistics demonstrates strong performance in key regions like Rift Valley and Western, backed by consistent contributions from top sales reps. However,to drive sustained growth, the business needs to address regional disparities—particularly by boosting sales in major regions like Nairobi and clean up reporting anomalies like the "Unknown" region.Standardizing sales strategies across all representatives and balancing model availability across all brands will help convert overall unit volume into long term market leadership and profits.





