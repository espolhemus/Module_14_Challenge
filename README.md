# Module_14_Challenge
Module 14 Challenge - CitiBike NYC Analysis

## Overview of Project
This project involves using Tableau to analyze data related to a bike sharing program in NYC and create visualizations and a Tableau Story to communicate those findings. 

### Purpose
The purpose of this challenge is to take a CSV file containing data related to the NYC Citi Bike bike-sharing program (from August, 2019) and to analyze that data and present analysis and visualizations that would help to inform and persuade potential investors considering launching a similar bike sharing program in Des Moines, Iowa. 

## Analysis
The results of efforts are as follows:

### Trips by Starting and Ending Location

- The following visualizations depict the number of trips begun at each of the various locations:

![Heatmap by Starting Location](/Images/Image001.png)
![Table by Starting Location](/Images/Image002.png)
![Bubble Chart by Starting Location](/Images/Image003.png)

- The following visualizations depict the number of trips ending at each of the various locations:

![Heatmap by Ending Location](/Images/Image004.png)
![Table by Ending Location](/Images/Image005.png)
![Bubble Chart by Ending Location](/Images/Image006.png)

- As one would expect, the most densely populated areas of Manhattan (specifically the Midtown area) accounted for the overwhelming majority of rides.   

### Trips by Date, Day of Week, and Time of Day, Aggregated and Broken Out by Gender

- The following visualization shows the distribution of trips over the course of the month:

![Trips by Date](/Images/Image007.png)

- The data shows strong ridership throughout the course of the month, with only two days have a total trip count of fewer than 60,000 trips.

- The following visualizations depict the number of trips taken by day of week and time of day, both in aggregate and broken out by gender, and also parsed by user type:

![Heatmap by Day and Time](/Images/Image008.png)
![Heatmap by Day and Time by Gender](/Images/Image009.png)
![Heatmap by Day Time Gender and User Type](/Images/Image010.png)

Unsurprisingly, the peak periods for ridership tend to be during the morning and evening rush hour commuting periods - however, ridership is remarkably strong and consistent throughout the course of the day on Saturdays and Sundays.  With regards to ridership by gender, Men make up the overwhelming majority of riders - however, the time of day trends appear to be similar across all genders.  With respect to ridership by Customer Status, non-Subscribers (referred to as Customers in the data) seem to concentrate the majority of their trips on the weekends 

### Trips by Duration, Aggregated and Broken Out by Gender

- The following visualization shows the distribution of rides by duration:

![Rides by Duration](/Images/Image011.png)

- A remarkable number of trips have a duration of 5 minutes or less, and there are very few trips with a duration of 30 minutes or more.

- The following visualization shows the distribution of rides by duration, broken out by gender:

![Rides by Duration and Gender](/Images/Image012.png)

- The data show similar trends in trip duration regardless of gender.

### Number of Rides by BikeID

- The following visualization shows number of rides associated with each BikeID:

![Rides by BikeID](/Images/Image013.png)

- As evidenced by the visualization, there are significant disparities in the number of rides taken by BikeID.

### Recommendations for Further Development

There are a number of recommendations for further development, including:

- Attempting to determine whether there is excess bike inventory in certain locations at certain times, and insufficient inventory at other locations.

- Quantifying the total time spent on trips by BikeID, to determine maintenance needs.

- Binning of locations based on the number of trips beginning and ending at specific locations, in an effort to identify those locations that may not be financially viable.

- Building metrics to determine the length of time that a BikeID went between rides, to determine when bikes should be repositioned between various stations.

- Determining what percentage of trips are "one way" (beginning and ending at different locations) versus "round trip" (beginning and ending at the same location).

## Link to Tableau Public

The Tableau Story can be found at:
[link to dashboard](https://public.tableau.com/app/profile/erin.polhemus/viz/Module_14_Challenge_16494536696590/CitbikeStory)

