# Vancouver Crime Rates Project

## The purpose of this project is to analyze crime data gathered from https://www.kaggle.com/datasets/tcashion/vancouver-bc-crime-dataset/ to understand the crime rates and crime type over the course of 2003 to 2023. The core components of this project inlclude:
* Cleaning and transforming data gathered from kaggle
* Exploratory data analysis to gather insight on trends over time and the various types of crimes that occur
* Develop an interactive dashboard that summarizes the analysis and data with Tableau (https://public.tableau.com/app/profile/victor.yung/viz/CrimeVancouverDashboard/Dashboard1)

## Data
* year
* month
* day
* time
* street name
* X and Y coordinates
* Longitude and Latitude

## Exploratory Data Analysis
---
In this project, I wanted to emphasize the overall trend of crime rates and crime types from 2003 to 2023 in the Vancouver region. Timing of day is an important factor to understand therefore, I transformed and split the datetime column into various components. The first compnoent is Year-month column gives us the counts/frequency of crimes that have occured within a specific timeframe. The second component is timestamp which is transformed into categorical variables (6-12 = MORNING , 12 - 18 = AFTERNOON , 18 - 24 = EVENING , 24 TO 6 = OVERNIGHT).

From the timeseries plot below, there has been a downward trend of crime rates occuring over the years. From 2003 to 2023 we are experiencing a 43% drop in total crime rates within the Vancouver region.
![Screen Shot 2024-07-12 at 10 25 37 AM](https://github.com/user-attachments/assets/1afd3014-e91e-4a70-8df3-2ea4c124ae0d)

Overall, we notice that Theft from Vehicle was a large proportion of the type of crime occurred followed by Other Theft over the range of 20 years. However, the most stagnant of offences comes from Vehicle Collisions or Pedrestian Struck (with Fatality) and Homicides.
<img width="897" alt="Screen Shot 2024-07-12 at 10 31 44 AM" src="https://github.com/user-attachments/assets/bd9f641b-a5ce-4cd9-9372-b1cf7efe856b">
<img width="894" alt="Screen Shot 2024-07-12 at 10 32 32 AM" src="https://github.com/user-attachments/assets/70c28f1b-7fd8-46f9-bb15-fc663d26f795">

Addtionally, majority of the crimes taken place would between Midnight and Evening which is expected to see.
<img width="878" alt="Screen Shot 2024-07-12 at 10 33 45 AM" src="https://github.com/user-attachments/assets/30e6157c-2da8-4d78-bfc8-258490ca0d0d">




   
