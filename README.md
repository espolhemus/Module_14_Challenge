# Module_14_Challenge
Module 14 Challenge - CitiBike NYC Analysis

## Overview of Project
This project involves using Tableau to analyze data related to a bike sharing program in NYC and create visualizations and a Tableau Story to commicate those findings. 

### Purpose
The purpose of this challenge is to take a CSV file containing data related to the NYC Citi Bike bike sharing program (from August, 2019) and to analyze that data and present analysis and visualizations that would help to inform and persuade potential investors considering launcing a similar bike sharing program in Des Moines, Iowa. 

## Analysis
The results of efforts are as follows:

### Trips by Starting and Ending Location

- The following visualizations depict the number of trips begun at each of the various locations:

![Heatmap by Starting Location](/Images/Image_001.png)
![Table by Starting Location](/Images/Image_002.png)
![Bubble Chart by Starting Location](/Images/Image_003.png)

- The following visualizations depict the number of trips ending at each of the various locations:

![Heatmap by Ending Location](/Images/Image_004.png)
![Table by Ending Location](/Images/Image_005.png)
![Bubble Chart by Ending Location](/Images/Image_006.png)

As one would expect, the most densely populated areas of Manhattan (specifically the Midtown area) accounted for the the overwhelming majority of rides.   
 
### Filtering by User Specified Criteria

- In order to filter the dataset based on user-specified criteria, the user can enter values into one or more than one of the following fields:

![Filter Criteria](/images/filter_criteria.png)

- In order to apply the user-specified criteria, the user simply enters a value into the text box, and then applies the criteria by pressing Enter, Tab, or by using their mouse to click within a different field.  The user can enter multiple filter criteria - however, in order to remove the filters which have been applied, the user must reload the HTML page.

### Results of User-Specified Search

- The results of a user-specified search appear as follows:
 
![Post Filter](/images/post_filter.png)

## Summary of Analysis
 
### Drawbacks

- The simplistic approach that was taken in developing this solution has resulted in a number of significant drawbacks - in particular, the search criteria is case-sensitive, which is a significant limitation and impediment impacting the utility of the solution, and the fact that the user must reload the page in order to clear any previously-applied filter criteria is likely to result in significant user frustration, and a negative perception of the site. 

### Recommendations for Further Development

There are a number of recommendations for further development, including:

- Adding the ability to sort the resulting table based on the column headings.

- Adding a button to enable the user to clear existing filters and restore the entire corpus of data without having to reload the page.

- Adding functionality to enable searches to be executed regardless of the case of the input values and the values within the dataset.

- Converting certain of the text boxes (e.g. "Country", "Shape") into dropdown menus containing a list of the values that are actually present in the dataset.

- Enabling date-based searches to be performed for periods of time other than a single day (e.g. for an entire month).
