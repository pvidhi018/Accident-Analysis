# Road Accident Analysis

## Project Overview

This project explores road accident and casualty data using two datasets to identify patterns related to accident severity, vehicle safety features, casualty demographics, and accident timing.

The first dataset focuses on vehicle occupants, including impact speed, seatbelt use, airbag availability and deployment, injury severity, and accident details. The second dataset focuses on road casualties, including accident date and time, weather, road surface, lighting conditions, casualty type, age, gender, and injury severity.

Through data cleaning, exploratory data analysis (EDA), and visualizations, this project aims to make accident-related data easier to understand and highlight patterns that may support road safety analysis.

## Project Objectives

- Clean datasets by handling missing values and duplicate records or columns.
- Analyze accident and injury severity patterns.
- Explore the relationship between vehicle safety features and accident outcomes.
- Compare frontal and non-frontal accidents.
- Identify patterns by age group, gender, and casualty type.
- Examine accident trends across years and different times of day.
- Present findings through charts and a correlation heatmap.

## Dataset 1: Vehicle Occupant and Safety Analysis

This dataset contains information about vehicle occupants and accident characteristics, including:

- Impact speed
- Survival status
- Airbag availability and deployment
- Seatbelt usage
- Frontal and non-frontal collisions
- Occupant age and gender
- Accident year and vehicle manufacturing year
- Injury severity levels (1, 2, and 3)
- Case ID

### Data Cleaning and Analysis

- Handled missing values and duplicate records.
- Reviewed summary statistics, including age, accident year, and vehicle manufacturing year.
- Compared frontal and non-frontal collisions.
- Analyzed survival status and injury severity.
- Explored the correlation between vehicle manufacturing year and airbag deployment.

### Key Findings

- Occupant ages ranged from 1 to 97 years where the age group between 16 - 36 years affected most.
- The average accident year was approximately 1999.
- Vehicle manufacturing years ranged from 1953 to 2002, with an average around 1992.
- Frontal collisions were more frequent than non-frontal collisions, with approximately 16,000 frontal and 9,000 non-frontal cases.
- The dataset contained more survivors than fatalities.
- Drivers were more affected than other occupant groups in the analysis.
- Injury severity level 3 was the most frequent category in the chart.
- The correlation heatmap showed a weak positive correlation of approximately 0.3 between vehicle manufacturing year and airbag deployment.

## Dataset 2: Road Accident and Casualty Analysis

This dataset includes information about accident date, time, road surface, lighting, weather, casualty type, injury severity, gender, and age.

### Data Cleaning and Analysis

- Removed duplicate columns.
- Analyzed casualty age groups and their accident counts.
- Compared accident counts across years and time periods: daytime, noon, night, and midnight.
- Examined the distribution of casualties by age.
- Compared the number of affected drivers, passengers, and pedestrians.
- Analyzed casualty class by gender.

### Key Findings

- Adults represented the age group with the highest number of accidents in the analysis.
- Accident counts across the examined time periods declined from 2010 to 2016.
- The 18–30 age group had the highest casualty count in the age distribution.
- Drivers were the most frequently affected casualty group, followed by passengers and pedestrians.
- Male casualties outnumbered female casualties across the analyzed classifications, except in the passenger category.

## Tools and Techniques used in Analysis

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Summary statistics
- Data visualization
- Correlation analysis and heatmaps

**Tools:** Add the specific tools you used, such as Python, Pandas, NumPy, Matplotlib, Seaborn, Excel, or Power BI, as applicable.

## What are the Project Outcomes

This project demonstrates how road accident datasets can be cleaned, analyzed, and visualized to identify patterns in collisions, injury severity, survival outcomes, and casualty demographics.

The findings can support further investigation into road safety, vehicle safety features, and groups or circumstances associated with higher casualty counts.

## To conclude

By analyzing two complementary datasets, this project provides a broader view of road accidents—from vehicle occupant safety and collision characteristics to casualty demographics and accident timing. It demonstrates the value of data cleaning, exploratory analysis, and visual storytelling in extracting useful insights from real-world datasets.
