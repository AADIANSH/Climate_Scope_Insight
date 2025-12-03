Milestone 1 – DV ClimateScope 

1. Dataset Information

Original dataset size: 106,013 rows × 41 columns

Countries covered: 150+, including Afghanistan, Albania, Algeria, India, USA, etc.

Contains data from multiple locations within each country

No missing values detected

No duplicate rows found

2. Data Cleaning Steps

Converted the last_updated column into proper datetime format

Checked and removed duplicates (none were present)

Standardized all measurement units:

Temperature → Celsius

Wind speed → kph

Precipitation → mm

Visibility → km

Pressure → mb

Saved the cleaned dataset as cleaned_weather.csv

3. Data Transformation

Extracted month from the last_updated column

Converted daily data into monthly averages

Grouped records by month, country, and location_name

Saved the aggregated output as monthly_weather.csv

4. Deliverables

✔ cleaned_weather.csv – Fully cleaned dataset

✔ monthly_weather.csv – Monthly aggregated dataset

✔ Milestone 1 Summary – Documentation of all steps

Milestone 2 – DV ClimateScope
1. Dataset Used

Input file: monthly_weather.csv

Contains monthly average values grouped by month, country, and location

Includes 26 numeric and categorical fields (temperature, humidity, precipitation, air quality indicators, etc.)

2. Visualization Steps

✔ Temperature Trends

Compared monthly average temperatures for India and the USA

Line chart used: Month on X-axis, Avg Temperature (°C) on Y-axis

✔ Humidity Distribution

Analyzed humidity levels for India, USA, and Australia

Boxplots used to show variation and spread

✔ Air Quality Comparison

Compared PM2.5 levels across India, USA, and China

Bar chart used to highlight pollution differences

✔ Correlation Heatmap

Generated a heatmap for all numeric variables

Observed patterns such as PM2.5–PM10 correlation, temperature–humidity relationship, etc.

3. Deliverables

All visualizations (temperature, humidity, air quality, correlations)

Insights summarized in this milestone document

Dataset used: monthly_weather.csv

Milestone 3 – DV ClimateScope 
1. Dataset Used

Aggregated monthly dataset (monthly_weather.csv)

Variables include temperature, humidity, precipitation, PM2.5, PM10, and other air-quality indicators

2. Advanced Analysis Steps

✔ Seasonal Trends

Studied seasonal patterns of temperature and humidity for India

Compared both variables using line charts

✔ Anomaly Detection

Used boxplots to detect outliers in India’s temperature and PM2.5 levels

Identified unusual temperature values and pollution spikes

✔ Predictive Analysis

Built a simple linear regression model to forecast India’s temperature for the next 6 months

Compared actual vs predicted values visually

✔ Statistical Relationships

Used scatterplots with regression lines to study relationships between variables

Example: Temperature vs Humidity, PM2.5 vs PM10

3. Deliverables

Graphs for seasonal trends, anomalies, forecasts, and regression insights

Detailed milestone summary with key findings

Dataset used: monthly_weather.csv


Milestone 4 – DV ClimateScope 
1. Dataset Used
- Input file: monthly_weather.csv
- Contains monthly aggregated climate and air quality indicators across 150+ countries
- Variables include: temperature, humidity, precipitation, PM2.5, PM10, wind speed, UV index, visibility, and pressure
- Dataset already cleaned and transformed in previous milestones

2. Advanced Visualization & Dashboard Steps
✔ Interactive Dashboard Integration
- Combined all major visuals (temperature trends, humidity distribution, air quality comparison, correlation heatmap) into a single Power BI dashboard
- Added slicers for Country and Month to enable dynamic filtering
- Ensured all charts update simultaneously when filters are applied
✔ Geo-Spatial Mapping
- Implemented Map visual to show country-wise PM2.5 and PM10 levels
- Used bubble size and color scale to represent pollutant intensity
- Enabled drill-down to view seasonal variations per country
✔ Polishing & Professional Layout
- Standardized chart titles, legends, and axis labels for clarity
- Applied consistent color scheme:
- Temperature → Blue
- Humidity → Green
- PM2.5 → Red
- PM10 → Orange
- Balanced layout with 2×2 grid arrangement for visuals and slicers on top panel
✔ Narrative & Insights
- Added text box summarizing key findings:
- Seasonal temperature and humidity patterns
- Strong correlation between PM2.5 and PM10
- Country-wise pollution hotspots visible on map
- Prepared spoken-style explanation script for presentation

3. Deliverables
- Final Power BI Dashboard with all integrated visuals
- Geo-Spatial Map showing pollutant distribution across countries
- Interactive Filters & Slicers for country and month selection
- Milestone 4 Summary Document with polished layout and presentation insights
