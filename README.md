# Urban Air Quality and Respiratory Health Analysis
## Overview 
This project aims to analyze the impact of urban air quality on respiratory health using a comprehensive dataset that includes air quality measurements from various cities worldwide. The analysis compares different pollutants (CO, Ozone, NO2, and PM2.5) and their contributions to the Air Quality Index (AQI) values.

## Dataset
The dataset used for this analysis is the Global Air Pollution Dataset, containing the following columns:
- **Country**: The country where the air quality data was collected
- **City**: The specific city of measurement within the country
- **AQI Value**: The overall Air Quality Index value
- **AQI Category**: The classification of the AQI value (Good, Moderate, Unhealthy)
- **CO AQI Value**: The AQI value for Carbon Monoxide
- **Ozone AQI Value**: The AQI value for the Ozone
- **NO2 AQI Value**: The AQI value for Nitrogen Dioxide
- **PM2.5 AQI Value**: The AQI value for PM2.5

The dataset can be found here (https://www.kaggle.com/datasets/hasibalmuzdadid/global-air-pollution-dataset)

## Problem Statement
Urban air pollution is a critical public health issue linked to various respiratory diseases and health complications. This project aims to address the following questions:
1. How do different pollutants contribute to overall air quality measured by AQI?
2. Which pollutants are most prevalent in regions with unhealthy air quality?
3. What insights can be drawn regarding the relationship between specific pollutants and health risks associated with poor air quality?

## Methodology
The following steps were taken to conduct the analysis:
1. Data preparation:
   - Load the dataset into a Jupyter Notebook
   - Install pandas, matplotlib, and seaborn to read, clean, and analyze the dataset
   - Check the dataset for missing values and filter for relevant columns

2. Data visualization:
   - Use boxplots to visualize the distribution of AQI values for each pollutant across different regions
   - Use comparative visualizations to highlight which pollutants are most significant in areas with unhealthy air quality

3. Statistical Analysis:
   - Conduct a correlation analysis to determine the relationships between different pollutants and overall AQI values
   - Identify trends and patterns in pollutant levels across various cities and countries

4. Reporting Results:
   - Document findings through visualizations, statistical summaries, and interpretations
   - Discuss implications for public health policies aimed at improving urban air quality

## Results

**Correlation Analysis**
   - Strong relationships between various pollutants and the overall AQI were revealed. PM2.5 showed a high correlation of 0.98 with AQI values indicating that this pollutant worsens the AQI significantly.
   - PM2.5 is a critical factor in determining air quality and its associated health risks.

**Pollutant Contributions**
   - Pollutants Pm2.5 and ozone have the highest AQI values in the unhealthy AQI category, emphasizing the need for targeted pollution control measures.

**Visualizations**
   - Boxplot:
        - PM2.5 consistently exhibits the highest median AQI value among all pollutants analyzed, indicating it is a major contributor to poor air quality in urban settings.
        - The interquartile range for PM2.5 is wider than that of CO and Ozone, suggesting greater variability in pollution levels across different regions.
        - Several outliers are present for PM2.5 recording exceptionally high AQI values classified as unhealthy. This highlights urgent policy attention to address severe air quality issues
        - In contrast, CO and NO2 show lower median AQI values and fewer outliers, suggesting they may not pose as significant a health risk as PM2.5 in most regions.
   - Barplot:
        - PM2.5 is shown as the most significant pollutant contributor in unhealthy regions, followed by Ozone.
        - CO and NO2 show comparatively lower average AQI values but still contribute to unhealthy air quality conditions.
        - The vast difference between PM2.5 AQI values and the other comparative pollutants highlights an urgent need for targeted intervention.
   - Plot for Countries:
        - The Republic of Korea shows a significant concern with having the highest average AQI value for PM2.5.
        - Bahrain and Mauritania follow as the next two countries with the highest average AQI values for PM2.5.
        - The ozone pollutant has the second highest average for AQI values classifying PM2.5 and Ozone as the most prevalent pollutants to target.
     
## Conclusion
The project provides valuable insights into urban air quality and its effects on respiratory health by leveraging data analysis techniques. The findings should contribute to a better understanding of how specific pollutants impact public health, ultimately informing strategies for mitigating air pollution in urban areas. The prevalence of high PM2.5 levels in Korea, Bahrain, and Mauritania highlights a pressing public health concern that necessitates immediate action. By implementing targeted policies aimed at reducing Pm2.5 emissions and enhancing public awareness about air quality issues, these countries can mitigate the associated health risks and improve overall respiratory health outcomes for their population.
