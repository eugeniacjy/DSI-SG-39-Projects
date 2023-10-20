# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Exploring climate data of Singapore

### 1. Project Problem Statement

Air-conditioning is popular for its ability to cool spaces rapidly. However, waste heat is generated in the cooling process. This waste heat can add up to 11 degrees Celcius to ambient temperatures, farther driving up demand for air-conditioning use, creating a self-perpetuating cycle.

In Singapore, it was observed that the rising temperatures experienced in 2022 led to increased demand for installation of air-conditioning units. Air-conditioning was also identified as a major contributor (24%) to household electricity use.

As an analyst with Cooling Singapore, a multi-disciplinary research group who is working on understanding and developing solutions for urban heat issues, you are investigating the relationship between temperature change and household electricity use.

Your research questions are:
* How have temperatures and household electricity use changed over time?
* How do high temperatures affect household electricity use within the year?

### 2. Data Sets

Data sets used for this analysis are:
* [Surface Air Temperature](https://data.gov.sg/dataset/surface-air-temperature-mean-daily-minimum) - Data for mean monthly minimum temperature. Data set contains 2 columns and 491 rows.
* [Household Electricity Consumption](https://www.ema.gov.sg/resources/singapore-energy-statistics/) - Data for mean monthly household electricity consumption by dwelling type. Data set contains 4 columns and 2283 rows.

### 3. Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**mean_temp**|*float*|National Environment Agency data| Mean monthly minimum temperature recorded. Units are in degrees Celcius.| 
|**mean_overall_elect_use**|*float*|Energy Market Authority data| Mean monthly household electricity consumption across all dwelling types. Units are in Gigawatts per hour (GWh)| 

### 4. Conclusion

The analysis of mean minimum temperature and mean overall household electricity use uncovered that:
* Over time, there is an overall increase for both temperatures and household electricity use
* Within the calendar year, temperature and household electricity follow similar seasonal patterns - i.e. lower electricity use within cooler months of Jan/Feb, higher electricity use within hotter months of May/Jun
* There is a moderate positive correlation between temperature and household electricity use. The correlation score is 0.45

### 5. Recommendations
Given that temperature affects electricity use, we recommend exploring low energy cooling solutions to deal with the tropical heat, including:

* **Building natural shading structures to block sun's heat**

Rather than artifically cooling rooms through air-conditioning, we could explore building shade structures near windows that get heavy sunlight. This will prevent the sun's rays from reaching and heating up the room.

* **Planting trees to naturally reduce surface temperatures**


The presence of trees and vegetation lowers the recorded surface temperatures in an urban setting. Neighbourhoods with dense greenery have been observed to be 3 to 7 degrees Celcius cooler than heavily built up areas.

### 6. Sources

a. ['Business is booming': Air-con retailers, servicing firms struggle to cope with demand amid hot weather](https://www.channelnewsasia.com/singapore/aircon-sales-servicing-companies-retailers-strong-demand-2709076)

b. [Household Electricity Consumption Profile](https://www.nea.gov.sg/our-services/climate-change-energy-efficiency/energy-efficiency/household-sector/household-electricity-consumption-profile)

c. [Southeast Asia’s air conditioning is burning up the Earth](https://kontinentalist.com/stories/air-conditioning-in-southeast-asia-is-worsening-climate-change)

d. [What Asia’s trees tell us about heat inequality](https://kontinentalist.com/stories/who-trees-dont-shield-from-the-urban-heat-island-effect)