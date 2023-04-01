# AirQualityIndex

The project titled "An Exploration of the Association Between Political Affiliation and AQI Levels" is an open-ended exploratory data analysis project that aims to explore the potential relationship between political affiliation and air quality index (AQI) levels. The project involves conducting a guided EDA analysis on new data, with a focus on particle matters of AQI, specifically NO2 and SO2. The project aims to draw insights into the potential causes of AQI concentrations between countries and the relevance and impact of SO2 on AQI calculations. The project hypothesizes that countries leaning left will have a lower average annual AQI level than those leaning right, and aims to predict a country's yearly average AQI with 75% accuracy given its political standpoint. Overall, the project offers an intriguing opportunity to investigate the potential relationship between politics and air quality, providing important insights for policymakers and citizens alike.

Tools Used:

Data cleaning and analysis: Python (Pandas, NumPy, SciKitLearn)
Data visualization: Matplotlib, Seaborn, Tableau

Analysis:
We conducted a guided EDA analysis on their new dataset to explore the association between political affiliation and AQI levels. We focused specifically on the particle matters of AQI, namely NO2 and SO2. We cleaned the data by converting the datetime column into distinct columns for each day and month and creating a pivot table of latitude vs. longitude to find the average AQI for each combination. We joined a table of the average AQI over the year for NO2 and SO2 through the country code and then visualized the data using various plots, including a bar graph and a heatmap.

We found that the average concentration of NO2 throughout a year is overall way higher than SO2 in most countries, and that there exist hotspots within the data where both particles have a stronger presence than outside of those regions. We also speculated about potential causes of these patterns, such as certain powerful and common industries producing a large amount of a certain pollutant, or differences in political affiliation and environmental policies.

Future Work:
To further investigate the association between political affiliation and AQI levels, we could conduct regression analysis to quantify the relationship between the two variables. We could also gather more data on specific environmental policies and their implementation in different countries to better understand their impact on AQI levels. Additionally, we could explore the relationship between AQI levels and other variables, such as population density or climate.
