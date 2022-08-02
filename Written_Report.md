# Kickstarting with Excel

## Overview of Project
	This Project focuses on basic excel functionalities and the creation of pivot tables and graphs to display
information related to data.
 
### Purpose
	Activities showcase ability to construct pivot tables in excel, utilize formulas and functions including
COUNTIFS(), SUM(), and basic mathematical operations, and making charts to display time-data. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
	This analysis includes the creation of a PivotTable and chart that show the amount of kickstarter campaigns for three
outcomes, 'successful', 'failed', and 'canceled', within the 'theater' Parent Category. The values are shown across each month
and can be filtered by Parent Category or Years. 

### Analysis of Outcomes Based on Goals
	This analysis includes the creation of new columns and a chart showing the outcomes of the projects based on the 
goal values for the projects. The columns tally the number of projects based on outcome and they are separated by row based
on the value of each project's goal. The chart plots the percentage of the projects for each outcome across a line displaying
the value of the projects' goals in increasing order from 'Less Than 1000' to 'Greater than 50000'.	

### Challenges and Difficulties Encountered
	One of the major challenges was determining the correct placements of Fields in the PivotTable construction.
Excel offers a wide array of functionality for PivotTables, but for this project there was an image for the desired
table and chart to be constructed. The solution included applying the 'Months' field in the Row and 'outcomes' in the Columns
and Values sections. Another challenge was the proper input of COUNTIF() parameters to properly apply
filters to the selected data. This meant that proper attention was needed while writing the parameters for the 
outcome, goal value, and subcategory criteria, specifically with the numerical values of the goal.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
	1. In the theater category, there are more successful projects than failed projects in all months of the year.
	2. For projects in the theater category, there are the greatest number of successful projects launched between 
	April and June. 

- What can you conclude about the Outcomes based on Goals?
	For plays, the percentage of successful projects decreases as goal value increases, except for values in the 
range of 30000 to 40000.

- What are some limitations of this dataset?
	There is no metadata for the spotlight or staff_pick columns so it leaves the user to infer what the Boolean data values can be 
interpreted as meaning. Similarly there is no metadata specifying if the different currency types are reflected in the 'goal' and 'pledged' 
columns or if they are all in USD in those columns regardless of the 'country' and 'currency' designation.


- What are some other possible tables and/or graphs that we could create?
	Pie charts or stacked bar charts showing the percentage of successful, failed, and cancelled campaigns based on ranges of goal amounts 
or ranges of time between deadline and creation date.