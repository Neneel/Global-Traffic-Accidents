# Global-Traffic-Accidents
This repository contains detailed information about the Global Traffic Accident Analysis

# PROJECT TITLE: Global Traffic Accidents Insights

[Introduction](Introduction)

[Data Description](Data-Description)

[Methodology](Methodology)

[Visualizations](Visualizations)

[Findings](Findings)


## INTRODUCTION

Accidents are a major public safety concern, and understanding their causes and patterns is crucial for effective policy making. Governments rely on data-driven approaches to enhance road safety, improve emergency response systems, and implement preventive measures. This dataset provides critical insights into accident occurrences by capturing key details such as date, time, location, weather and road conditions, and accident causes. By analyzing these factors, policymakers can develop targeted interventions to reduce accident rates and mitigate their impacts.

This study aims to assist government agencies and policymakers in identifying trends and risk factors associated with traffic accidents. With detailed records on accident occurrences, authorities can formulate evidence-based policies to enhance road safety, allocate resources efficiently, and develop preventive strategies such as stricter traffic regulations, improved road infrastructure, and better emergency response systems.

### Problem Statement

A lack of comprehensive data analysis on accident causes, environmental conditions, and high-risk areas limits the ability of policymakers to implement effective safety measures. This research seeks to bridge that gap by providing a data-driven approach to understanding accident trends and informing policy decisions that enhance road safety.

### Objectives

1.	Identify High-Risk Areas and Trends: Analyze accident occurrences by location and time to detect patterns and prioritize safety measures.
   
3.	Assess Environmental and Road Factors: Evaluate the impact of weather and road conditions on accident rates.
   
5.	Examine Causes and Contributing Factors: Identify leading causes of accidents to inform law enforcement and public safety initiatives.
   
7.	Enhance Global Safety Strategies: Use accident data to inform international best practices and collaborative safety initiatives.
   
9.	Support Policy Development: Provide data-driven recommendations for traffic regulations, road maintenance, and awareness campaigns.


### Research Questions

1.	What are the most common causes of traffic accidents, and how do they vary across different regions?
   
3.	How do weather and road conditions influence the frequency and severity of accidents?
   
5.	What trends can be observed in accident occurrences over time and geographic locations?
   
7.	What roles do vehicle involvement and casualty rates play in assessing accident severity and response strategies?
   
9.	How can accident data be used to improve traffic regulations and road infrastructure policies?
    

## DATA DESCRIPTION

The dataset used in this study comprises detailed records of traffic accidents, including the following key attributes:

•	Accident ID: A unique identifier for each accident report.
•	Date: The date when the accident occurred (YYYY-MM-DD format).
•	Time: The specific time of the accident (HH:MM format).
•	Location: The city and country where the accident happened.
•	Latitude & Longitude: GPS coordinates pinpointing the exact location of the accident.
•	Weather Condition: The weather at the time of the accident (e.g., Clear, Rain, Fog, Snow).
•	Road Condition: The state of the road surface at the time of the accident (e.g., Dry, Wet, Icy, Snowy).
•	Vehicles Involved: The number of vehicles affected in the accident.
•	Casualties: The total number of injuries and fatalities caused by the accident.
•	Cause: The primary reason for the accident (e.g., Speeding, Drunk Driving, Distracted Driving).

Tools used
Data cleaning: Microsoft Excel and PowerBI
Data analysis: PowerBI
Visualization: PowerBI

METHODOLOGY
Data Collection and Cleaning:  The dataset was downloaded from Kaggle.com and the following measures were taken to clean the dataset.
•	Reassigning Unique Identifiers: New Accident ID were generated and re-assigned to make it unique and organized.
•	Handling Duplicates: No duplicates were found.
•	Data Type Conversion – Changed data from one type to befitted type (e.g Date, Time columns).
•	Normalization – Ensuring consistency in data types (e.g., all dates in DD-MM-YYYY format).

Exploratory Data Analysis (EDA): Statistical and graphical techniques are used to explore trends, distributions, and relationships between variables. Frequency distributions help identify common accident causes. Visualization tools like bar charts, line graphs, and histograms are employed to highlight patterns over time, accident hotspots, and high-risk conditions. Correlation analysis is conducted to assess relationships between variables such as weather conditions, road surface states, and accident severity.

Pattern and Trend Analysis: Advanced analytical techniques are applied to detect recurring patterns in accident occurrences. Time series analysis is used to observe fluctuations in accident frequency over different periods, helping identify seasonal trends and peak accident times. Geospatial analysis is conducted using mapping tools to pinpoint high-risk locations based on accident density, allowing policymakers to focus on accident-prone areas. 

FINDINGS
1.	High-risk spots: Saelo Paulo, Brazil has the highest number of accidents at 1,032 followed by New York, USA at 1,016. Lowest risk area is Berlin, Germany at 958, followed by Mumbai, India at 987.

2.	Environmental and road factors: Dry Road contributes the highest percentage of accidents at 17.29%. Comparing road and weather conditions, there are more casualties when the road is wet, and weather is clear.

3.	Drunk Driving is the highest cause of accidents at 1.72k: There are more casualties when the weather is foggy, and there’s Reckless Driving, also when it is raining, and drivers are speeding.



RECOMMENDATIONS 
Targeted High-Risk Area Interventions
•	São Paulo and New York, with the highest accident rates, should implement stricter traffic enforcement, increased surveillance (e.g., AI-powered traffic cameras), and enhanced public awareness campaigns.
•	Investing in smart traffic management systems and stricter penalties for violations can reduce accident occurrences.
 Enhancing Safety in Low-Risk Areas
•	Berlin and Mumbai, with the lowest accident rates, can serve as models for effective road safety policies.
•	Governments should study their infrastructure, driver behavior, and law enforcement measures to replicate best practices globally.
Road Condition Awareness & Driver Education
•	Since dry roads contribute the highest percentage of accidents (17.29%), awareness campaigns should emphasize the risks of overconfidence in dry conditions.
•	Governments should introduce adaptive speed limits based on real-time road conditions to prevent over-speeding on dry roads.
Weather-Specific Safety Measures
•	Higher casualties occur when roads are wet, but weather is clear—suggesting drivers underestimate wet road risks. Governments should mandate enhanced traction control systems and improve road drainage in accident-prone areas.
•	During foggy or rainy conditions, stricter speed regulations and increased visibility measures (e.g., reflective road markers, improved street lighting) should be enforced.
Stronger Regulations on Drunk & Reckless Driving
•	With 1.72k accidents due to drunk driving, stricter alcohol consumption laws, increased sobriety checkpoints, and harsher penalties are necessary.
•	Governments should invest in public transportation alternatives and safe ride programs to reduce the need for impaired individuals to drive.
Mitigating Speeding Risks in Adverse Weather
•	Reckless driving during fog and speeding in rainy conditions significantly increase casualties. Automated speed control systems, stricter penalties, and better road signage in high-risk zones can reduce fatalities.
•	Encouraging adaptive vehicle technology such as automatic braking and collision avoidance systems can further enhance road safety.
Data-Driven Policy Development
•	Establishing global accident databases will help policymakers identify emerging trends and allocate resources efficiently.
•	Collaboration between cities and countries through knowledge-sharing initiatives will promote successful safety strategies worldwide.


