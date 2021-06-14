# Course-Project
Fatal Police Shootings 2015 – Present
Aaron Alejandro

Purpose & Users
The purpose of this dashboard is to enable the user to gain deeper insights into fatal police shootings in the United States through an interactive visualization. The users of this dashboard would be those who have an interest in identifying larger scale trends of police shootings, above and beyond what can be ascertained from seeing reports of individual events on the news. The dashboard enables the user to explore several different variables in relation to fatal police shootings.

Data
This dashboard is built using data from a GitHub database compiled by the Washington Post. Beginning on January 1, 2015, the source file contains records of all of the fatal shootings by police officers in the line of duty in the United States. Many dimensions of data are collected, including name, date, manner of death, age, gender, race, city, state, threat level, mental illness, and body camera. My visualizations will focus on gender, race, age, state, and date. The dataset is regularly updated and is constantly growing. I updated my file twice over the course of working on this project due to new records.

Questions answered
My dashboard seeks to answer each of the following questions: 
•	What is the distribution across races?
•	What is the distribution across gender?
•	What is the distribution across age groups?
•	Which states have the most shootings?
•	Is there seasonality to fatal shootings?
•	Is the number of fatal shootings per year increasing or decreasing?

In addition, I have set each dashboard component as drill-down filters, so that combinations of these questions can also be answered. For example, how does the distribution of fatal shootings across races change by age group? Which state had the most shootings in 2015 vs 2020?

Rationale
 
 
I chose to represent race and gender on pie charts because it is intuitive to think of these categories as parts of a whole. The slice at 12:00 on the race chart without a label represents null values, or records for which race was not available. 

One additional thing that would be helpful to include here would be how these figures compare to the general population. For example, the US Census Bureau states that Black Americans make up about 13% of the US population, yet they make up 24% of fatal police shootings. Males and females are split about 50/50 across the US population, but there is a large gender disparity when it comes to fatal police shootings. Even this would not tell the whole story though, because it would be helpful to show crime rates across these demographics if that is available.
 
 
I created bins for the continuous variable, age, in order to show the distribution in a more meaningful way. I made the choice to filter out all of the null values for which age was not collected in the data. The user can gain additional insights into each age bin by clicking on it. For example, across all age groups, the percent of black victims is 24%, but when we look only at the under 18 bin, that percent increases to 36%. A similar increase exists for all race groups except for white and null.

 
This visualization shows a time series of occurrences by month. There does not appear to be a clear seasonality to the shootings. I added a trendline to answer whether there is a clear trend upwards or downwards across the 5 years. This trendline shifts based on the state that is selected, so we can see some states such as California trend downwards, while other states such as Florida have trended upwards.

 This is another time series by month, but it calculates the running total. The different hues aren’t ordinal, they only correspond to different years so that it’s easier to differentiate the years vs if they were all the same color. This quickly shows that the cumulative fatal shootings per year across the US have been relatively similar since 2015. It appears that 2021 has had a slow start, since by this month there were more shootings in each year from 2015 – 2020. However, the month is not over and the datapoints are constantly growing.

 
This visualization uses a sequential color intensity scale to highlight the states with higher numbers of fatal shootings vs states with lower numbers. There is such a large gap between the highest (924) and second highest (551) states that I chose to adjust the endpoint for the color scale in order to make the differentiations in intensity more meaningful. 
Works Cited
Muyskens, J. (n.d.). Washingtonpost/data-police-shootings. GitHub repository. Retrieved April 16, 2021, from https://github.com/washingtonpost/data-police-shootings
U.S. Census Bureau QuickFacts: United States. (n.d.). Retrieved April 16, 2021, from https://www.census.gov/quickfacts/fact/table/US/PST045219

