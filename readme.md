# Extracting Insights from US Airbnb Data

## Project Overview
This project explores, analyzes, and integrates US Airbnb data to extract actionable insights for improving profitability and customer satisfaction. Using Python, we performed exploratory data analysis (EDA), advanced geospatial analysis, and integrated external data sources (e.g., crime data, museum data) to uncover patterns and relationships that can inform Airbnb’s decision-making.

## Objectives
The main objectives of this project were:
1. Conduct EDA to uncover patterns and relationships in the Airbnb dataset.
2. Apply advanced geospatial analysis to answer location-based questions.
3. Integrate external data sources to enhance the analysis and derive deeper insights.
4. Present actionable recommendations for Airbnb based on the findings.

## Problem Statement
Airbnb data alone does not provide the full picture of factors affecting profitability and customer satisfaction. By integrating external data such as population, crime rates, and museum reviews, this project aimed to uncover how these factors influence Airbnb performance in various locations, helping Airbnb target key areas for improvement and expansion.

## Methodology
### Dataset
The primary dataset includes:
- **Room Details**: Type, price, availability, minimum nights, and total reviews.
- **Host Data**: Host ID and number of listings.
- **Location Data**: Latitude, longitude, state, and city.

### Analysis
1. **Preprocessing and EDA**:
   - Cleaned the dataset, removing missing or irrelevant data.
   - Conducted statistical analysis and visualizations to understand Airbnb distributions by price, room type, location, and availability.

2. **Advanced Topics**:
   - Geospatial Analysis:
     - Determined geographical boundaries for room types and calculated area size.
     - Identified the closest "Private Room" to the USS Midway.
   - Correlation Analysis:
     - Explored relationships between Airbnb reviews and crime rates in California.
     - Analyzed how museum ratings influence nearby Airbnb listings and reviews.

3. **Data Integration**:
   - Integrated Airbnb data with:
     - Gun crime data to study location safety and its impact on Airbnb performance.
     - Museum data to analyze the influence of cultural attractions on Airbnb listings.
     - US population data to assess the relationship between population density and Airbnb distribution.

### Deliverables
1. **Jupyter Notebook**: Contains all code for preprocessing, analysis, and visualization.
2. **Presentation**: Summarizes the methodology, insights, and actionable recommendations.
3. **Visualizations**: Maps, graphs, and charts generated during the analysis.

## Key Insights
1. **State-Level Analysis**:
   - Most Airbnb listings: California.
   - Cheapest state for Airbnb: Ohio.
   - Highest average price: Hawaii.
2. **Host Insights**:
   - Top 3,000 hosts account for ~50% of profits and manage 26% of all Airbnbs.
3. **Geospatial Analysis**:
   - The largest room-type polygon is for “Entire home/apt” in California, covering 79,538 km².
   - Museums with higher ratings tend to have fewer Airbnb listings nearby but correlate strongly with higher review activity.
4. **Crime and Population**:
   - Areas with higher gun crime rates tend to have fewer Airbnb reviews.
   - States with higher populations generally have more Airbnb listings.

## Recommendations
1. **Increase Representation**:
   - Target underrepresented states like Ohio for potential growth.
2. **Collaborate with Cultural Attractions**:
   - Partner with museums and attractions to enhance guest experiences.
3. **Safety and Marketing**:
   - Market Airbnbs in safer neighborhoods to attract more guests.
4. **Expand Data Collection**:
   - Record more detailed stay information and integrate additional external data for deeper insights.

## Conclusion
This project provided a comprehensive analysis of US Airbnb data, uncovering patterns and relationships that can guide Airbnb’s strategies for growth and customer satisfaction. By integrating external datasets and applying advanced analysis techniques, we delivered actionable insights to improve Airbnb's operations.
