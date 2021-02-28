# Communicate-Data-Findings
## Exploratory  and Explanatory Data Analysis of Bike Share Dataset

## Dataset

The data consists of information regarding individual rides made in a bike-sharing system covering the greater San Francisco Bay area. There were 4646 bikes. The data set contains 183412 rows or bike trips and 16 columns.


## Introduction

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, I used use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, I produced a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying the findings was done through transforming my exploratory visualizations from the first part into polished, explanatory visualizations.

## Why this project

Data visualization is an important skill that is used in many parts of the data analysis process. Exploratory data visualization generally occurs during and after the data wrangling process, and is the main method that was used to understand the patterns and relationships present in my data. This understanding aided in my statistical analyses and also in building conclusions and findings. Explanatory data visualization techniques were used after generating my findings, and were used to help communicate my results to others. Understanding design considerations ensures my message is clear and effective. In addition to being a good producer of visualizations, going through this project helped me to be a good consumer of visualizations that are presented to me by others.

## Summary of Findings

In the exploration, I found that there was an inverse relationship between a user's age and the duration of a bike trip. The  bike trip was shorter as a user's age increased. The gender distribution shows males are 3 times as likely to use the bike share program. However, comparing the the gender and trip duration we find that males have the shortest trip duration. A customer spends twice as much time on a trip than a subscriber. When the gender types are compared as it relates to trip duration, the ages between 20 to 40 represents the group that does most of the rides. Females and males do appear to have similar ride average. The trip duration start trending up on the weekends from Thursdays to Saturdays. Males still have the shortest bike trip.

## Key Insights for Presentation

The key focus of the presentation was the trip duration and how it was influenced by gender, age and user type and weekday usage. First I looked at the trip duration distribution and then plot the logarithmic scale transformation on a histogram. I then looked at how each user type was distributed using countplot because it is a category. A pie chat was used to better visualize that category using the percentage difference . I used the histogram to explore the daily usage among users and plot a bar chat to examine the gender members distribution. We derived the age from the column member_birth_year and plotted a histogram to display the distribution.

I then went on to do bivariate where I looked at the pairwise features between variables (trip duration and age) using a heat map then alternatively with a scatterplot. The heatmap was very good in visualising the data throught the variations in coloring for each variable. I explored the relation between trip duration and gender and user type. using boxplots. I had trim the top y-limit to 50 minutes to be able to view the boxplot clearly. The boxplot highlighted key summary metrics like the first and third quantiles, which correspond to the 25th and 75th percentiles. Median, the mid-point in the distribution, which also corresponds to the 50th percentile.Interquartile range (IQR), the width between the third and first quantiles. 

For my multivariae exploration I first explored the relationship between age, gender and the trip durations using a scatterplot. I used a line plot to compare how long each gender member rides on a given weekday.

## List of Sources

https://www.kaggle.com/chirag02/ford-gobike-data-analysis

https://seaborn.pydata.org/generated/seaborn.FacetGrid.html

https://github.com/meet3012/Ford-GoBike-System-Data-Visualization/blob/master/Data-Exploration-with-Bike-Data.ipynb

https://github.com/adipurnamk/Ford-GoBike-System-Data/blob/master/exploration_fordgobike_2017.ipynb
https://github.com/ijdev/Ford-GoBike-System-Data---Data-Analysis

https://mnalmelihi.github.io/z

https://www.citibikenyc.com/system-data

