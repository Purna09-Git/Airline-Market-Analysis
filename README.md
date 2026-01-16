# Airline Market Trends Analysis 


###  Project Overview
This project provides a deep-dive analysis into the U.S. domestic aviation market over three decades. By leveraging the **Consumer Airfare Report (Table 1a)**, the dashboard visualizes the complex relationships between flight distances, ticket pricing strategies, and the competitive dominance of major vs. low-cost carriers.

### Key Analytical Insights
* **Geospatial Dominance:** A Mapbox-integrated visualization showing carrier market share across major U.S. hubs, represented by proportional pie-chart markers.
* **Pricing vs. Distance Correlation:** A scatter plot analysis of `Lowest Fare` vs. `Distance (Nsmiles)`, identifying how origin cities and market competition impact low-cost carrier entry.
* **Historical Resilience:** A time-series analysis of passenger volume from 1993 to 2024, highlighting the significant "V-shaped" recovery following the 2020 global pandemic dip.
* **Operational Scale:** Comparative analysis of passenger volume and route distance filtered by the largest carriers in the market.

### Technical Toolkit
* **Data Visualization:** Tableau Desktop / Tableau Public
* **Data Source:** U.S. Department of Transportation (DOT) - Consumer Airfare Report: Table 1a
* **Key Metrics Analyzed:** `nsmiles`, `passengers`, `fare`, `carrier_lg` (leading carrier), and `large_ms` (market share).
