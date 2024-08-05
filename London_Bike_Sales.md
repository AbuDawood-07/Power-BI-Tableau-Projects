## London Bike Sales
Dashboard Link :
https://public.tableau.com/app/profile/dawood3998/viz/londonbikesales/Dashboard1?publish=yes

## Problem Statement
- This dashboard provides insights into London bike sales. It helps analyze trends over different time periods, understand the impact of weather conditions on sales, and track the total number of bikes sold. By examining these factors, stakeholders can make data-driven decisions to optimize sales strategies and inventory management.

## Steps Followed
- Data Collection and Exploration
- Data Source:

Collected data from Kaggle in CSV format.
Data Loading:

Loaded the dataset into Python using Pandas.
python
import pandas as pd
data = pd.read_csv('london_bike_sales.csv')

- Data Exploration:

Explored the dataset to understand its structure and identify missing values, outliers, and data types.




- Export to Excel:

Saved the manipulated data into an Excel file for use in Tableau.

data.to_excel('london_bike_sales_processed.xlsx', index=False)

- Dashboard Creation in Tableau
Data Loading:

Imported the processed Excel file into Tableau.

- Visualization:

Created various visualizations to represent the data insights:
Moving average of sales over different periods (day, week, month).
Moving average of duration by date.
Temperature vs. Wind Speed heatmap.
Total number of bikes sold.

- Filters and Interactivity:

Added filters for date, weather conditions, and sales periods.
Enabled interactive elements for dynamic exploration.

- Design and Layout:

Applied a consistent color theme and arranged visuals for intuitive navigation.
Dashboard Publishing:

- Report Insights
[1] Total Number of Bikes Sold
Total Bikes Sold: 25,894
[2] Moving Average of Sales Period
Daily Moving Average: Shows daily trends and seasonal patterns.
Weekly Moving Average: Highlights weekly fluctuations and peak periods.
Monthly Moving Average: Provides a broader view of monthly sales performance.
[3] Moving Average of Duration by Date
Daily Moving Average Duration: 2.5 hours
Weekly Moving Average Duration: 17.5 hours
Monthly Moving Average Duration: 75 hours
[4] Temperature vs. Wind Speed Heatmap
Heatmap Analysis:
High sales volumes correlate with moderate temperatures and low wind speeds.
Low sales volumes observed during extreme weather conditions.
[5] Additional Insights
Sales by Day: Highest sales observed on weekends.
Sales by Weather: Clear weather days show higher sales compared to rainy or snowy days.
Top Selling Months: July and August show peak sales, indicating a summer trend.

# Conclusion
The London Bike Sales dashboard offers valuable insights into sales trends, the impact of weather conditions on bike sales, and overall sales performance. By leveraging these insights, stakeholders can optimize sales strategies, improve inventory management, and enhance customer satisfaction.

