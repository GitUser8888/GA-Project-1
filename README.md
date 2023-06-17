# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Analysing Rainfall of Singapore

### Overview

This is the first project that is completed as part of the General Assembly Data Science Immersive curriculum. For the first project, we're going to analyze climate trends in Singapore. Climate refers to the general weather conditions prevailing over an area for a long period. There are several aspect to studying climate, in this project, we will be focusing on rainfall.


---

### Problem Statement

Climate change is a global issue that has led to increasing extreme weather variations and heavy rainfall amounts, including more intense and frequent El Nino and La Nina events. The existing urban infrastructure in Singapore, including drainage systems, canals, and reservoirs, that were designed based on historical weather patterns may not adequately address the heightened flood risks and surge from heavier rainfalls. Flash floods and prolonged inundation can cause severe disruptions, economic losses, and endanger lives. Given these pressing concerns, there is an urgent need to review and update Singapore's urban development plans, especially flood adaptation measures.
This project will analyse the rainfall trends from January 1982 to April 2023 in Singapore, and will seek to determine and justify the need for furthur studies and reviews on Singapore's urban development plans and flood adaptation measures to mitigate the effects of climate change.

---

### Datasets

There are 2 datasets included in the [`data`](./data/) folder for this project. These correponds to rainfall information. 

* [`rainfall-monthly-total-2023.csv`](./data/rainfall-monthly-total-2023.csv): This is the total monthly rainfall recorded in mm(millimetres) per month from January 1982 to April 2023.

* [`rainfall-monthly-number-of-rain-days-2023.csv`](./data/rainfall-monthly-number-of-rain-days-2023.csv): This is the number of rain days in a month recorded per month from January 1982 to April 2023.


---

### Data Dictionary:

|Feature|Type|Dataset|Description|
|---|---|---|---|
|no_of_rainy_days_in_month|int|monthly-number-of-rain-days-2023|Monthly number of rain days from 1982 to 2023. A day is considered to have “rained” if the total rainfall for that day is 0.2mm or more|
|total_rainfall_in_month|float|rainfall-monthly-total-2023|Monthly total rain recorded in mm from 1982 to 2023|


---

### Key Takeaways:

1. There is a slight positive correlation between the total rainfall and the number of rainy days in a month
2. Both the total rainfall and the number of rainy days in a month generally follow a normal distribution
3. There appears to be increased volatility of the increase and decrease of rainfall between the high and low rainfall cycles through the years, which supports the observation of increasingly extreme weather and rainfall variations


---

### Recommendations:

The recommended next steps include:

1. Analyse rainfall variations between each district of Singapore to prioritise efforts on districts that have higher rainfall and more prone to flooding, in the case of limited budget and resources
2. Build accurate models to predict the future amount of rainfall and length of extreme wet and dry periods, taking into account the extreme weather variations
3. Review existing drainage system and identify gaps in future-proofing flood and stormwater management measures
4. Review existing urban plans, especially for older estates, to determine and plug gaps in flood preparedness, as well as on-site mitigation measures such as detention tanks, green roofs, rain gardens or retention ponds
