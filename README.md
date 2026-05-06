#  Road Accident Analysis Dashboard — Power BI

## Project Overview:

This project analyzes road accident data to understand why accidents happen and where accidents are concentrated.
The dashboard is created using Microsoft Power BI to present clear insights through interactive visuals.

The report is divided into two pages:

1.Overview & Causes of Accidents

2.Location & Patterns of Accidents

## Objectives:

* Identify the major causes of road accidents.
 
* Analyze injuries and deaths caused by different factors.

* Find high-risk states and cities.

* Understand patterns related to human behavior and accident severity.
  
* Present insights using an interactive dashboard.
  
## Dataset:
The dataset used for this project is taken from the official Government of India open data portal:

 Source: Open Government Data (OGD) Platform India – https://data.gov.in/
 
You can access the dataset here:
Road Accident Data – https://drive.google.com/file/d/1xlDFthesZfBQdCDbQ7hi9GeAtmtfF8GL/view?usp=sharing

The dataset contains:

Accident causes (over speeding, careless driving, etc.)

Number of cases, injured, and deaths.

State / UT / City information.

Accident category details.

Data was cleaned and transformed before loading into Power BI.

## Data Cleaning Steps (Excel / Power Query):

* Removed unwanted and duplicate columns.
  
* Renamed unclear column names.
  
* Unpivoted cause columns to create a proper structure.
  
* Split data into Cause, Cases, Injured, Died.
  
* Removed errors and blank values.
  
## Dashboard Pages & Visuals:

### Page 1 — Overview & Causes:

* Cards (Total Cases, Injured, Died):
  
Shows the overall impact of road accidents at a glance.

 * Accidents by Cause (Bar Chart):
   
Displays which causes (over speeding, careless driving, etc.) lead to more accidents.

* Cause Contribution (Treemap):
  
Helps to visually compare the proportion of each accident cause.

* Cause vs Cases, Injured, Died (Column Chart):
  
Compares how each cause affects the number of cases, injuries, and deaths.

* Top 10 States by Deaths (Bar Chart):
  
Highlights the states with the highest number of accident deaths.

* Accident Category Analysis (Donut Chart):
  
Shows how accidents are distributed across different categories.

### Page 2 — Location & Patterns:

* Map of Accidents by State/UT:
  
Geographical view of where accidents are concentrated.

* Top 10 Cities by Accidents (Bar Chart):
  
Identifies cities with the highest accident cases.

* Injured vs Died by State (Column Chart):
  
Compares injury and death counts across states.

* Death Rate by Cause (Line Chart):
  
Shows which causes result in higher death rates.

* Detailed Table View:
  
Provides complete data for deeper analysis and filtering.

## Key Insights:

1. Over speeding is the leading cause of accidents.

2. Careless driving is the second major reason.
   
3. Some states and cities show consistently high accident numbers.
 
4. Injuries are much higher than deaths, showing scope for better emergency response.
 
5. Human behavior causes more accidents than weather or vehicle issues.

6. Driving under influence shows a high death rate.

## Tools Used:

Microsoft Power BI — Dashboard creation

Microsoft Excel — Data cleaning

## Conclusion:

This dashboard helps to quickly understand accident trends, risky regions, and major causes, which can support awareness and decision-making for road safety improvements.

### Video Explanation:
https://drive.google.com/file/d/1rCy2XqSc0QlRMW-Ub9ZeiNdJzNvropNm/view?usp=sharing
