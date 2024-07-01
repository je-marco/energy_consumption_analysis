# Dynamic Analysis of Daewoo Steel Year 2018 Energy Consumption 

![overview](https://github.com/je-marco/energy_consumption_analysis/blob/9e9b43cb2ac0440782d3aa2510998916e3074688/overview.png)

## Overview
This project is about analyzing the energy consumption of Daewoo Steel Co. Ltd, a small-scale steel manufacturing plant using a dynamic dashboard in Excel.

## Scope
The energy usage included in this analysis included both electricity consumption during production processes and/or facility operations for the year 2018. 

## Objective 
* Understand energy consumption and use historical data to identify pattern and trends.
* Identify peak usage times.
* Detect irregularities and inefficiencies in energy use.

## Here are the questions I was interested in answering using the dashboard
* What is the total energy consumption?
* What is the average energy usage per month and per day?
* What is the daily fixed usage?
* How much reactive power is being used?
* Which load type has the highest energy and reactive power consumption?
* When does peak energy usage occur?
* Is the electricity being used efficiently?
* Are there any anomalies in energy use?

## I took the following steps to create my analysis
* Extracting and loading the data from UC Irvine Machine Learning Repository.
* Conducting exploratory data analysis (EDA) to prepare and analyze the data.
* Summarizing data with pivot tables to identify key performance indicators (KPIs).
* Adding charts to the dashboard, creating slicers and linking tables for filtering.
* Formatting the dashboard and applying a consistent theme.

## Here are my key takeaways from the dataset
* Monthly energy usage averages around 79,790 kWh, with January nearly doubling this amount. September and December have the lowest usage, each under 60,000 kWh.
* The fixed daily usage, when only essential loads are running with no production, averages 308.07 kWh.
* Maximum loads consume the most energy and lagging current reactive power, while medium loads use the most leading current reactive power. Consistently, January also has the highest reactive power usage. However, the months of October and November should be investigated further since the reactive power usage (kVArh) during those months is relatively higher as compared to months with the same amount of electricity usage (kWh).
* Peak usage times are from 9 AM to 4 PM.
* The average monthly lagging power factor, indicating the efficiency of electricity usage, ranges from 74% to 89%. Only in January, February, and December does it consistently meet or exceed the ideal 85%.

## Recommendation  

### Enhance data collection for better monitoring  
* Collect data on production hours and loads: Track energy consumption per production unit.
* Gather machine-level data: Identify equipment that may be inefficient, outdated or in need of maintenance.
* Monitor process-level data: Understand energy usage per area.
* Assess raw material variability: Identify how it affects energy consumption.

### Implement energy optimization measures
* Conduct energy audit: Conduct a comprehensive analysis of energy usage and find opportunities for energy saving.
* Optimize production schedules:
  * Pinpoint energy-intensive processes and schedule them on off-peak hours when energy costs are lower.
  * Shut down less energy-efficient equipment sets when there is an increase in production demand.
* Incorporate advanced power systems: Use automatic power factor correction systme to manage reactive power.
* Reduce fixed energy usage:
  * Lighting: Install motion sensors to activate lights only when needed.
  * Ventilation: Localize and automate ventilation with timers or occupancy sensors.
  * Computers: Use energy-saving settings.
* Invest in energy-efficient technologies and equipment: Explore financing options like tax incentives and carbon credits to offset costs and risks.
* Employee training and awareness: Educate employees about energy-saving practices and encourage a culture of energy efficiency.

## References: 
* V. E., Sathishkumar, Shin, Changsun, and Cho, Yongyun. (2023). Steel Industry Energy Consumption. UCI Machine Learning Repository. https://doi.org/10.24432/C52G8C.
