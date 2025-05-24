# Exploratary Data Analysis in Hospitality Analysis

## PROBLEM STATEMENT
Atliq Grands operates hotels in three major cities in India and has been a prominent player in the hospitality industry for two decades. However, with evolving market dynamics and fierce competition, the company has seen a drop in revenue and market share. This project focuses on analyzing booking patterns, customer preferences, and revenue trends to recommend data-driven solutions to improve their business performance.

## EXPLORATARY DATA ANALYSIS (EDA)
Key insights extracted from the analysis:
Platform Analysis: Distribution of bookings across various platforms (e.g., direct, OTA).
Outlier Detection: Handled outliers in revenue and guest counts using statistical methods (3σ rule).
Room Category & City Performance: Identification of high-performing and underperforming room types and cities.

## DATA CLEANING AND TRANSFORMATION
Removed records with zero or negative guest count.
Filtered extreme outliers in revenue_generated and revenue_realized.
Validated data consistency for room categories and property capacity.

## Key Insights
Standard rooms have the lowest average occupancy (~57.89%) compared to Premium (58.03%), Elite (58.01%), and Presidential (59.28%).
Occupancy is consistently higher during weekends across all room categories and cities.
Average occupancy across major cities is consistently between 50% and 60%.
The average customer rating is below 4 in all major cities analyzed.

## Recommadations
Consider promotional offers, room upgrades, or repositioning to boost Standard room demand.
Implement dynamic pricing with higher weekend rates and introduce weekday discounts to balance occupancy.
Focus on improving service quality, cleanliness, and responsiveness. Collect more qualitative feedback to understand pain points.
Cities with sub-55% occupancy require attention. Explore marketing strategies, local partnerships, or service differentiation in these areas.

## Tools & Technologies Used
Python 
Pandas
Matplotlib
Seaborn
