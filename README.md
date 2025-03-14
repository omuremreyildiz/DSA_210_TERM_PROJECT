Car Accident Risk Analysis in Turkey (2019-2023)
Project Overview
This project aims to analyze car accident data across different cities in Turkey for the years 2019 to 2023. The goal is to evaluate the risk of being involved in a traffic accident, including the likelihood of injury or death, for each city in Turkey. By visualizing these risks on a map, we will identify the most dangerous and the safest cities in terms of traffic accidents. The project will also calculate probabilities related to the risk of accidents and their potential outcomes (injuries or fatalities) in each city.

Motivation
With the increasing number of vehicles on the road, road safety has become a major concern in many countries, including Turkey. Understanding the patterns of accidents and the risk associated with each city will help policymakers, insurance companies, and citizens make informed decisions regarding road safety. This project aims to provide a data-driven analysis to highlight which cities have the highest and lowest risks of traffic-related accidents.

Data Source
The data used for this project will consist of the following:

Vehicle Numbers by City (2019-2023): The number of vehicles registered in each city of Turkey for the past five years.
Number of Accidents by City (2019-2023): The total number of car accidents recorded in each city during this period.
Number of Accidents with Injury/Death by City (2019-2023): The number of accidents resulting in injury or death in each city during this period.
These data will be sourced from [official Turkish traffic reports], [municipal data portals], or other publicly available government data sources. If necessary, data enrichment will be done by combining external data sources such as population data, road infrastructure details, and other traffic indicators.

Data Collection Plan
Vehicle Numbers Data: This data will be sourced from government transport or traffic departments in Turkey (e.g., TÜİK) or municipal sources.
Accident Data: I will collect data on the number of traffic accidents from traffic authorities or public datasets available via government websites or transportation agencies.
Data Enrichment: I will enhance the data by incorporating additional variables such as population size or road density to make my analysis more comprehensive.
Data Analysis Plan
Data Cleaning: I will begin by cleaning the data to handle missing or incorrect values. This will ensure that the dataset is ready for analysis.
Exploratory Data Analysis (EDA): The next step will be conducting EDA to understand the distribution of accidents, the relationship between the number of vehicles and accidents, and the frequency of injury/fatality.
Risk Calculation:
Calculate the probability of getting into a car accident in each city by dividing the number of accidents by the number of vehicles in each city.
Calculate the probability of injury or death by dividing the number of accidents resulting in injury or death by the total number of accidents.
Mapping & Visualization: Using Python libraries (like Folium and Plotly), I will create a color-coded map where each city will be highlighted based on the level of traffic risk, with probabilities displayed when hovering over each city.
Expected Findings
The project will provide a detailed comparison of traffic risks across different cities in Turkey.
The map will help visualize which cities have the highest risk of traffic accidents, injury, and fatalities.
The calculated probabilities will provide a quantitative understanding of the likelihood of getting into an accident and the chances of an accident resulting in injury or death in each city.
Limitations and Future Work
Data Quality: The analysis depends on the availability and accuracy of the data. Any missing or incomplete data could affect the reliability of the findings.
Temporal Factors: While the data covers five years, it may not account for yearly fluctuations in traffic patterns, road conditions, or policy changes that could impact accident rates.
Geographic Granularity: The analysis is limited to the city level; however, further analysis could explore smaller geographic areas such as neighborhoods or specific intersections.
Future Work
Investigate correlations with weather, road conditions, and other factors that could influence accident rates.
Explore the use of machine learning models to predict accident hotspots or factors contributing to accidents based on more complex datasets.
