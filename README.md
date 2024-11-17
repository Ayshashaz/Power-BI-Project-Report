New York City Airbnb Dashboard
Overview
This project involves a Power BI dashboard that provides an analytical overview of Airbnb listings in New York City. The dashboard is designed so that it would help stakeholders understand key trends, patterns, and insights within the Airbnb market of New York City.
•	Interactive Visualizations: Easily explore data by neighborhood, room type, and price range.
•	Trend Analysis: Identify patterns in availability, pricing, and occupancy rates.
•	Insights for Decision-Making: Provides actionable insights for hosts, guests, and policymakers.
Loading of The Dataset and Data Preprocessing:
The project commenced with data extraction from Kaggle.com, followed by converting the dataset into Excel format for ease of use. Data transformation and preprocessing were performed using Power Query, which included removing duplicate records, handling null values through appropriate replacements, and restructuring the dataset. Columns were rearranged and renamed to enhance the dataset's clarity and usability, ensuring it was well-prepared for analysis.
Visualizations and Insights:
1. Bar Chart: Top 10 Neighborhoods by Average Price
Insight:
This chart highlights the top 10 neighborhoods with the highest average listing prices. It provides a clear comparison to help identify premium areas within the city.
Fields Used:
•	Axis: Neighborhood
•	Values: Average of Price
Key Findings:
•	Manhattan neighborhoods dominate the top spots, showcasing their high demand and premium pricing.
2. Map: Geographical Distribution of Listings
Insight:
The map provides a spatial view of Airbnb listings, indicating their distribution across New York City.
Fields Used:
•	Location: Latitude, Longitude
•	Values: Price
Key Findings:
•	Listings are densely clustered in Manhattan and Brooklyn, while areas like Staten Island have fewer listings.
3. Pie Chart: Proportion of Room Types
Insight:
This chart illustrates the breakdown of listings by room type, offering insights into guest preferences and market trends.
Fields Used:
•	Legend: Room Type
•	Values: Count of ID
Key Findings:
•	Entire homes/apartments account for the majority of listings, followed by private rooms. Shared and hotel rooms make up a smaller proportion.
4. Line Chart: Trends in Bookings Over Time
Insight:
The line chart tracks booking trends over time, highlighting seasonal patterns and demand fluctuations.
Fields Used:
•	Axis: Date (or Created Month)
•	Values: Count of ID
Key Findings:
•	Booking activity peaks during holiday seasons, indicating increased demand during these periods.
5. Stacked Bar Chart: Listings per Neighborhood Group
Insight:
This chart displays the number of listings in each neighborhood group, providing insights into area-wise listing distribution.
Fields Used:
•	Axis: Neighborhood Group
•	Values: Count of ID
Key Findings:
•	Brooklyn and Manhattan have the highest number of listings, reflecting their popularity among hosts and guests.
6. Table: Detailed Summary of Listings
Insight:
The table provides a comprehensive overview of Airbnb listings with essential details such as listing ID, name, host name, price, and minimum nights.
Fields Used:
•	ID, Name, Host Name, Price, Minimum Nights
7. Donut Chart: Minimum Nights Stayed by Room Type
The donut chart shows the minimum number of nights stayed by room type, which makes us understand the type of room hosts are more comfortable.
Fields used:
•	Legend: Room Type
•	Values: Minimum Nights Spend
Key Findings:
•	It shows most of the people preferred to purchase the entire home for staying longer nights.

CONCLUSION:
The analysis of Airbnb data in New York City revealed the following key trends and patterns:
1.	Neighborhood Distribution: Listings are highly concentrated in neighborhoods like Manhattan and Brooklyn, showcasing their popularity among hosts and guests.
2.	Pricing Trends: Average prices vary significantly by neighborhood, with Manhattan having the highest average nightly rates.
3.	Room Type Preference: Entire homes/apartments dominate the listings, indicating a strong preference for privacy among guests.
4.	Occupancy Insights: Some neighborhoods show high occupancy rates, indicating potential profitability for hosts.
5.	Seasonal Patterns: Booking rates and prices fluctuate seasonally, highlighting periods of high demand.

# Power-BI-Project-Report
