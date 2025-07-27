Project Overview
This project analyzes Uber ride fare data to uncover business insights using Python for data preparation and Power BI for visualization. The goal is to understand fare distribution, time-based trends, and the relationship between fare and distance to support pricing strategies and operational decisions.

Project Details
Course: INSY 8413 – Introduction to Big Data Analytics

Instructor: Prof. Eric

Students: Maniraguha Teta, Kevin

Date: July 2025

Tools Used
Python (Jupyter Notebook): For data cleaning, feature engineering, and initial exploratory data analysis (EDA).

Power BI Desktop: For data modeling, visualization, and creating an interactive dashboard.

Dataset
Source: Kaggle – Uber Fares Dataset

Key Fields:

fare_amount: The fare for the ride.

pickup_datetime: Timestamp of pickup.

pickup_longitude/latitude, dropoff_longitude/latitude: Coordinates for pickup and dropoff locations.

passenger_count: Number of passengers.

Data Cleaning & Feature Engineering (Python)
Steps Performed:
Removed invalid fares: Filtered out negative, zero, or extremely high fares.

Cleaned coordinates: Removed coordinates outside valid NYC bounds (if applicable).

Handled missing values: Dropped or imputed missing data.

Created new features: Extracted hour, day, month, and weekday from pickup_datetime.

Output:
Cleaned and enhanced dataset saved as uber_features.csv.

Power BI Dashboard
Key Visualizations:
Fare Distribution:

Histogram and box plot to analyze central tendency, skewness, and outliers.
![](./fare%20amount%20vs%20month.png)

Time-based Trends:

Line charts for average fare by hour, ride volume by hour/day/month, and weekday vs. weekend comparisons.
![](./fare%20amount%20vs%20hour.png)

Fare vs. Distance:

Scatter plot showing the positive correlation between fare and distance.
![](./fare_vs_disttance.png)

Busiest Periods:

Visualizations highlighting peak hours, months, and segmentation of peak vs. off-peak demand.
https://screenshots/busiest_periods.png

Dashboard Design:
Layout: KPIs at the top, trends and distributions in the center, filters at the bottom.

Interactivity: Slicers for month, weekday, and hour to allow dynamic filtering.

Consistency: Uniform theme, colors, and fonts for clarity.

Insights & Results
Fare Distribution: Most rides fall within the $5–$15 range, with a right-skewed distribution (median fare: $8–$10). Outliers exist above $50.

Peak Demand: Highest ride volumes occur during morning (6–9 AM) and evening (4–7 PM) commuting hours, as well as on weekends (Fridays and Saturdays).

Fare Trends: Average fares rise late at night, likely due to surge pricing or longer rides.

Fare vs. Distance: Strong positive correlation, though fare variability increases with distance.

Recommendations
Dynamic Pricing: Implement surge pricing during peak hours (6–9 AM, 4–7 PM) and weekends.

Off-Peak Promotions: Offer discounts or loyalty rewards during low-demand periods to balance ridership.

Data Validation: Monitor outlier fares (above $50) to ensure data accuracy.

Enhanced Analysis: Integrate external factors like weather or event data for deeper insights.

Conclusion
The Power BI dashboard provides a comprehensive view of Uber fare trends, enabling data-driven decisions for pricing and operations. Future improvements could include additional external datasets for richer analysis.

Files Included
uber_features.csv: Cleaned and engineered dataset.

uber_analysis.pbix: Power BI dashboard file.

ASSINMENT I.pptx: Presentation deck summarizing the project.

screenshots/: Folder containing dashboard visuals.

How to Use
Open uber_analysis.pbix in Power BI Desktop to explore the interactive dashboard.

Refer to ASSINMENT I.pptx for a detailed overview of the analysis.

Use the screenshots for quick reference to key visuals.

Contact
For questions or further information, please contact:

Maniraguha Teta

Kevin
