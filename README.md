# 🏨 Hotel Booking Analysis

## 📌 Problem Statement
Atliq Grands, a leading hotel chain operating across three major Indian cities, has recently experienced a decline in revenue and market share amidst growing competition and changing consumer behavior. This project aims to analyze booking patterns, customer preferences, and revenue trends  to recommend data-driven solutions to improve their business performance.

## 🧰 Technologies & Tools Used
- **Python** – Core programming language  
- **Pandas** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization

## 🧪 Project Workflow

### 1. 🧹 Data Cleaning & Transformation
- Removed records with zero or negative guest counts.
- Filtered out extreme outliers in `revenue_generated` and `revenue_realized` using statistical techniques (3σ rule).
- Ensured consistency across room categories and verified property capacities.

### 2. 📊 Exploratory Data Analysis (EDA)
- **Platform Analysis**: Analyzed booking distribution across channels such as Direct and OTA (Online Travel Agencies).
- **Outlier Detection**: Detected and handled anomalies in revenue and guest counts using statistical methods (3σ rule).
- **Room Category & City Performance**: Identified top-performing and underperforming room types and cities.


### 3. 🔍 Key Insights
- **Occupancy Rates**:  
  - Standard: 57.89%  
  - Premium: 58.03%  
  - Elite: 58.01%  
  - Presidential: 59.28%
- **Weekend Demand**: Significantly higher occupancy on weekends.
- **City-Level Performance**: Overall occupancy remains between 50–60% in all cities.
- **Customer Satisfaction**: Ratings consistently below 4, indicating service-related issues.

### 4. 💡 Recommendations
- **Boost Standard Room Demand**: Launch promotions, consider complimentary upgrades, or rebrand standard rooms.
- **Dynamic Pricing Strategy**: Increase weekend rates, offer weekday discounts to improve overall occupancy balance.
- **Service Improvement**: Focus on cleanliness, staff responsiveness, and collect more qualitative feedback from guests.
- **City-Level Strategy**: For cities with <55% occupancy, implement localized marketing campaigns, partner with local businesses, and tailor services to regional preferences.




