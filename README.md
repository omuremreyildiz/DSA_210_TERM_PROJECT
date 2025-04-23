# Car Accident Risk Analysis in Turkey (2019-2023)

## Project Overview

This project analyzes car accident data in Turkey from 2019 to 2023 with a focus on **vehicle type**. The goal is to evaluate how the type of vehicle impacts the likelihood of injury or death in traffic accidents. Through extensive exploratory data analysis (EDA), statistical testing, and visualization, the project seeks to uncover trends and differences in accident outcomes between vehicle categories such as cars, trucks, motorcycles, and more.

## Motivation

Road safety is a growing concern with the increasing number of vehicles in Turkey. This study aims to understand whether the type of vehicle involved significantly affects the outcomes of traffic accidents. Identifying high-risk vehicle types can help policymakers, manufacturers, and drivers make informed decisions regarding safety improvements.

## Data Collection Plan
**Vehicle Numbers Data**, **Accident Data** and **Death and Injury Data from Accidents**: will be provided from the website of TÜİK. The links of the webpages which has the excel data the project will use are as following:

Karayolu Trafik Kaza İstatistikleri, 2023 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2023-53479

Karayolu Trafik Kaza İstatistikleri, 2022 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2022-49513

Karayolu Trafik Kaza İstatistikleri, 2021 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2021-45658#:~:text=T%C3%9C%C4%B0K%20Kurumsal&text=%C3%9Clkemiz%20karayolu%20a%C4%9F%C4%B1nda%202021%20y%C4%B1l%C4%B1nda,ise%20%C3%B6l%C3%BCml%C3%BC%20yaralanmal%C4%B1%20trafik%20kazas%C4%B1d%C4%B1r.

Karayolu Trafik Kaza İstatistikleri, 2020 : https://data.tuik.gov.tr/bulten/index?p=karayolu-trafik-kaza-istatistikleri-2020-37436#:~:text=T%C3%9C%C4%B0K%20Kurumsal&text=%C3%9Clkemiz%20karayolu%20a%C4%9F%C4%B1nda%202020%20y%C4%B1l%C4%B1nda,ise%20%C3%B6l%C3%BCml%C3%BC%20yaralanmal%C4%B1%20trafik%20kazas%C4%B1d%C4%B1r.

Karayolu Trafik Kaza İstatistikleri, 2019 : https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2019-33628#:~:text=T%C3%9C%C4%B0K%20Kurumsal&text=%C3%9Clkemiz%20karayolu%20a%C4%9F%C4%B1nda%202019%20y%C4%B1l%C4%B1nda,ise%20%C3%B6l%C3%BCml%C3%BC%20yaralanmal%C4%B1%20trafik%20kazas%C4%B1d%C4%B1r.


## Data Analysis Plan

- **Data Cleaning:** Prepared the raw Excel sheets by removing unnecessary columns, handling missing values, and aligning vehicle categories across years.
- **Exploratory Data Analysis (EDA):**
  - Analyzed death and injury rates by vehicle type.
  - Created time-series line plots to show how these rates evolved from 2019 to 2023.
  - Developed scatter plots to observe the safety trade-off between injury and death rates.
- **Statistical Testing:**
  - Conducted ANOVA test
  - ANOVA is appropriate for comparing means across multiple groups (vehicle types)

## Key Hypothesis

**"Vehicle type does not change death and injury rate."**

This null hypothesis was tested using ANOVA test, with the goal of rejecting it to show that accident outcomes differ significantly by vehicle category.

## Visualizations

- **Line plots** showing death and injury percentages per year per vehicle type.
- **Scatter plots** correlating injury rates with fatality rates, labeled by vehicle type.

## Expected Findings

- Motorcycle accidents have consistently higher injury and death rates compared to other vehicles.
- Heavier vehicles (e.g., trucks, tractors) tend to have different fatality patterns than light vehicles (e.g., cars, minibuses).
- Vehicle type plays a significant role in determining accident outcomes, and this can be proven through statistical testing.

## Limitations

- **Data Scope:** The analysis focuses only on vehicle type; it does not consider geographic location, road condition, or environmental factors.
- **Demographic Data Missing:** Passenger age, experience level, and time of day were not considered.

## Future Work

- Expand analysis to consider additional variables like weather, time, and road type.
- Incorporate machine learning models to classify high-risk vehicles or predict accident outcomes.
- Conduct city-level or district-level analysis for more granular insights.

---

**Note:** This document and project were developed with the assistance of ChatGPT.
