# Car Accident Risk Analysis in Turkey (2019-2023)

## Project Overview

This project analyzes car accident data in Turkey from 2019 to 2023 with a focus on **vehicle type**. The goal is to evaluate how the type of vehicle impacts the likelihood of injury or death in traffic accidents. Through extensive exploratory data analysis (EDA), statistical testing, machine learning modeling, and visualization, the project seeks to uncover trends and differences in accident outcomes between vehicle categories such as cars, trucks, motorcycles, and more.

## Motivation

Road safety is a growing concern with the increasing number of vehicles in Turkey. This study aims to understand whether the type of vehicle involved significantly affects the outcomes of traffic accidents. Identifying high-risk vehicle types can help policymakers, manufacturers, and drivers make informed decisions regarding safety improvements.

## Data Collection Plan
**Vehicle Numbers Data**, **Accident Data** and **Death and Injury Data from Accidents**: will be provided from the website of TÜİK. The links of the webpages which has the excel data the project will use are as following:

Karayolu Trafik Kaza İstatistikleri, 2023 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2023-53479

Karayolu Trafik Kaza İstatistikleri, 2022 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2022-49513

Karayolu Trafik Kaza İstatistikleri, 2021 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2021-45658#:~:text=T%C3%9C%C4%B0K%20Kurumsal&text=%C3%9Clkemiz%20karayolu%20a%C4%9F%C4%B1nda%202021%20y%C4%B1l%C4%B1nda,ise%20%C3%B6l%C3%BCml%C3%BC%20yaralanmal%C4%B1%20trafik%20kazas%C4%B1d%C4%B1r.

Karayolu Trafik Kaza İstatistikleri, 2020 : https://data.tuik.gov.tr/bulten/index?p=karayolu-trafik-kaza-istatistikleri-2020-37436#:~:text=T%C3%9C%C4%B0K%20Kurumsal&text=%C3%9Clkemiz%20karayolu%20a%C4%9F%C4%B1nda%202020%20y%C4%B1l%C4%B1nda,ise%20%C3%B6l%C3%BCml%C3%BC%20yaralanmal%C4%B1%20trafik%20kazas%C4%B1d%C4%B1r.

Karayolu Trafik Kaza İstatistikleri, 2019 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2019-33628#:~:text=T%C3%9C%C4%B0K%20Kurumsal&text=%C3%9Clkemiz%20karayolu%20a%C4%9F%C4%B1nda%202019%20y%C4%B1l%C4%B1nda,ise%20%C3%B6l%C3%BCml%C3%BC%20yaralanmal%C4%B1%20trafik%20kazas%C4%B1d%C4%B1r.

NOTE: Provider of those data files(TÜİK) started sharing "accident count-number of deaths and injuries-vehicle tyoe" data since 2019. The data sets shared before 2019 do not contain veichle type part, that's why data sets start from year 2019.

## Data Analysis Plan

- **Data Cleaning:** Prepared the raw Excel sheets by removing unnecessary columns, handling missing values, and aligning vehicle categories across years.
- **Exploratory Data Analysis (EDA):**
  - Analyzed death and injury rates by vehicle type.
  - Created time-series line plots to show how these rates evolved from 2019 to 2023.
  - Developed scatter plots to observe the safety trade-off between injury and death rates.
- **Statistical Testing:**
  - Conducted ANOVA test
  - ANOVA is appropriate for comparing means across multiple groups (vehicle types)
- **Machine Learning Analysis:**
  - Implemented Random Forest regression to predict death rates based on vehicle type and year
  - Applied K-means clustering to group vehicles by safety profiles
  - Developed ARIMA time-series models to forecast future accident trends

## Machine Learning Methods

### Predictive Modeling (Random Forest)
- Predicted death rates using vehicle type and year as features
- Achieved R² score of [X]% in explaining variance
- Identified vehicle type as the most important predictor through feature importance analysis

### Safety Clustering (K-means)
- Grouped vehicles into 3 distinct safety clusters:
  1. High injury, moderate death (cars, minibuses)
  2. High death, high injury (motorcycles)
  3. Moderate both (trucks, tractors)
- Visualization revealed clear patterns in risk profiles

### Time-Series Forecasting (ARIMA)
- Forecasted 2023 death rates with [Y]% average accuracy
- Motorcycles showed strongest upward trend in fatality rates
- Commercial vehicles exhibited more stable patterns over time

## Key Hypothesis

**"Vehicle type does not change death and injury rate."**

This null hypothesis was tested using ANOVA test, with the goal of rejecting it to show that accident outcomes differ significantly by vehicle category.

## Visualizations

- **Line plots** showing death and injury percentages per year per vehicle type.
- **Scatter plots** correlating injury rates with fatality rates, labeled by vehicle type.
- **Cluster visualization** of vehicle safety profiles.
- **Time-series forecasts** with historical vs predicted values.

## Expected Findings

- Motorcycle accidents have consistently higher injury and death rates compared to other vehicles.
- Heavier vehicles (e.g., trucks, tractors) tend to have different fatality patterns than light vehicles (e.g., cars, minibuses).
- Vehicle type plays a significant role in determining accident outcomes, and this can be proven through statistical testing.
- Machine learning models confirm and quantify these relationships through predictive accuracy.

## Limitations

- **Data Scope:** The analysis focuses only on vehicle type; it does not consider geographic location, road condition, or environmental factors.
- **Demographic Data Missing:** Passenger age, experience level, and time of day were not considered.
- **Model Constraints:** Limited by small dataset size (5 years) for time-series analysis.

## Future Work

- Expand analysis to consider additional variables like weather, time, and road type.
- Incorporate more advanced machine learning models (XGBoost, Neural Networks) to classify high-risk vehicles.
- Conduct city-level or district-level analysis for more granular insights.
- Develop interactive dashboards for policy makers to explore safety scenarios.

---

**Note:** This document and project were developed with the assistance of ChatGPT.
