# Project 1: Where in the World is Carmen SanDiego retiring to?

### Problem Statement

This study aims to provide valuable insights into optimal retirement destinations, examining key factors such as Gross National Income (GNI), cost of living, and life expectancy across different countries. Targeting individuals nearing retirement age, as well as financial planners and advisors, the analysis explores the complexities of retirement preparation. Additionally, it addresses the needs of individuals who prioritize financial stability and aspire to retire early, recognizing their distinct goals in achieving financial independence and early retirement.


# Data Dictionary

|**2014-2023_gni**|*int*|Gapminder|GNI per capita per country from 2014 to 2023 (units in US dollars)| 
|**2014-2023_life_expectancy**|*float*|Gapminder|population life expectancy rates per country from 2014 to 2023 (units in years)|
|**happiness_2014-2022**|*float*|Gapminder|Happiness score per country in a period from 2014-2022 (units are meassured by happiness score 0-100)|
|**col_monthly_2023**|*float*|WorldPopulationReview|The cost of living in US dollars monthly per country in 2023| 
|**mean_gni**|*float*|Calculated|The average GNI per capita for a given country over 10 years|
|**std_gni**|*float*|Calculated|The standard deviation of the GNI for a given country|
|**mean_happ**|*float*|Calculated|The average happiness score per country over 10 years|
|**std_happ**|*float*|Calculated|The standard deviation of happiness score per country, used to determine if most people in the population experience similar levels of happiness|
|**mean_life_expectancy**|*float*|Calculated|The average life expectancy per country over 10 years|


# Datasets 

This project explored 4 different data sets: 

- life_expectancy.csv: Life Expectancy by Country
- gni_per_cap_atlas_method_con2021.csv: Gross National Income (GNI) per   capita in current US dollars
- happiness_score.csv: Happiness Score by Country
- cost_of_living_2024.csv: Average monthly cost of living per Country


**Investigations into in the data**

- Are countries with higher GNI best for retirement? 
- Is there a correlation between gni and cost of living?
- Is there a correlation between cost of living and the happiness score?
- Of the countries ranked with the highest happiness scores, which countries have the lowest cost of living?
- Which of these countries have the highest life expectancies 

**Executive Summary**

In order to find the perfect retirement spots, we sought locations that offered affordability, long-term economic stability, and a high level of overall happiness among their populations. A significant aspect of this analysis revolved around average life expectancy, which serves as an essential indicator of both happiness and economic well-being.

In our assessment of long-term economic stability, we analyzed countries' average Gross National Income (GNI) over the past decade, aiming to identify patterns and fluctuations within their economies. We noted that nations with higher GNIs typically had higher costs of living, leading to the identification of a middle ground to accommodate retirees with fixed incomes. Additionally, we prioritized countries with consistently high average happiness scores, reflecting a stable level of satisfaction among their populations. Notably, our analysis revealed that countries with higher GNIs showed minimal variance in life expectancy compared to those with middle-income statuses, guiding us towards prioritizing countries offering a balanced mix of quality of life and affordability for retirement prospects.

In summary, Brazil, Peru, Iran, Poland, and Uruguay emerge as the top contenders for retirement destinations. Among these countries, Brazil stands out for its affordable rent and second-highest happiness score. On the other hand, Uruguay boasts the highest rent among the group but also holds the highest happiness score. These findings highlight the diverse yet promising options available for retirees seeking an ideal balance of affordability and happiness in their chosen retirement location.