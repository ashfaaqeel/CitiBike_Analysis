<h1>CitiBike_Analysis</h1>

## Overview
This project analyzes CitiBike’s New York City bike-share data to understand user patterns and popular usage trends. CitiBike, launched in May 2013, is one of NYC’s largest public bike-sharing systems and has become a vital part of the city's transportation network.

## Languages and Libraries Used
- **Python** and **SQL**
- **Pandas**, **NumPy** and **Sqlalchemy** for data processing
- **Matplotlib** and **Seaborn** for visualizations

## Objectives
The main objective of this analysis is to answer the following questions:
- How many CitiBikes are there in NYC?
- What are the top 20 most popular stations where customers start their trip?
- What is the difference in average trip duration for subscribers vs. non-subscribers?
- What are the top routes by subscribers?
- what number of trips by age and gender for users under 90 years old

## Dataset
**Source**: [CitiBike System Data](https://www.citibikenyc.com/system-data)

**Columns**:
- **Trip Data**: Trip Duration, Start Time, Stop Time
- **Station Data**: Station ID, Station Name, Latitude, Longitude
- **User Data**: Bike ID, Birth Year, User Type (Subscriber or Customer), Gender

## Analysis Performed
1. **Exploratory Data Analysis (EDA)**: Basic cleaning, handling of missing values, transformation of columns, and understanding the dataset to derive insights.
2. **Descriptive Analysis**: Statistical summaries to understand average trip durations, station usage counts, and demographic distribution.
3. **Visualizations**:
   - Trip Duration Distribution
   - Peak Usage Hours
   - Popular Start Stations

## Insights
- **Peak Usage Hours**: Commuter rush hours (8-9 AM and 5-6 PM) have the highest ride frequencies.
- **Trip Duration**: Most trips are under 15 minutes, suggesting high demand for short-distance commutes.
- **Popular Stations**: *Pershing Square North* and *Grand Central Terminal* are among the busiest stations.
- **Demographics**: The majority of users are male, with a significant portion of subscribers versus one-time customers.

## Recommendations
- **Optimize Bike Availability**: Increase bike availability at popular stations during peak hours.
- **Rebalance Strategies**: Improve bike rebalancing operations at high-traffic stations.
- **Marketing**: Create campaigns to attract more female riders and occasional customers.

