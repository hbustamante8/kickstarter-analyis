# Kickstarting with Excel

## Overview of Project

### Purpose
	The purpose of the analysis is uncovered how different campaigns fared in relation to their launch dates and funding goals. The Kickstarter data set was used to create visualizations and use for analysis of different theater plays that were fundrasied for. There are 4114 entries in the data set about different types of fundraising campaigns along with other details of goal amount, pledged amount, outcome, etc. Through use of pivot tables, excel formulas, filtering, and pivot charts, analysis on this data was performed.

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date

	I performed this analysis for deliverable #1 by creating a new column by the name of “Years” that was based on another column, “Data Created Conversion”. From there, I created a pivot table in a new worksheet that showed specifically theater outcomes based on their launch date. The pivot table created contains two filters. One for “Parent Category” which is set to theater and one for “Years” that can allow for a specific year of outcomes to be seen. To show the visual representation of this pivot chart, a line chart was created (see image below).

<img width="362" alt="image" src="https://user-images.githubusercontent.com/96553992/147893401-fdee7fe8-630f-4db9-a036-645076e9d116.png">

 

### Analysis of Outcomes Based on Goals

	For the second deliverable, a new sheet was created along with eight columns and twelve rows to capture the outcomes based on goal fundraising amounts for different goal fund raising ranges. Using the “COUNTIFS()” function, the number of campaigns within each goal range were counted for all plays within the dataset. From there, the “SUM” function was used to find the total amount of projects for each goal range so that percentages for successful, failed, and canceled outcomes could be calculated. A line chart was then created to show the information in the sheet visually (see below).

<img width="482" alt="image" src="https://user-images.githubusercontent.com/96553992/147893406-b25a54a5-4e73-4643-a6e6-f5657c3af4cf.png">

 

### Challenges and Difficulties Encountered

	No significant issues was encountered throughout the analysis but something that could have created possible challenges were if the percentage failed, percentage successful, and percentage canceled lines were similar. This would make this graph less useful and would force there to perhaps be different criteria to be added into the “COUNTIFS” function statements. A difficulty that I found within the dataset was “live” option within outcomes. It is not clear as to what that means and perhaps this could add to the story being told in the analysis.

## Results

### Conclusions on Theater Outcomes by Launch Date
	The first conclusion that can be made from the Outcomes based on Launch Date visual is that the most successful theater fundraising campaigns begin in May and June. Secondly, failed outcome are most likely to happen in the month of October for theaters.

### Conclusion on Outcomes based on Goals

	From the Outcomes based on Goals it can be concluded that the lower the goal amount under $20,000, a fundraising campaign for plays is more likely to succeed. Interestingly, fundraising campaigns between $35,000 and $45,000 have a good chance of being successful. While campaigns greater than $45,000 have a very low high failure rate and should be avoided.

### Limitations and potential challenges
	A limitation of this dataset is the absence of specific area data within a country the fundraising campaigns will launch in. Having this data could help determine where specifically in a country it would be more likely to have success in raising money for a fundraising event. Another limitation of the dataset is not knowing how the many is being raised for each campaign.The dataset does not have data on whether the fundraising campaigns were door to door asking for pledges, online marketing, fundraising events, etc. Having this data could identify patterns between fundraising strategies and outcome of fundraising campaigns.

### Recommendation for additional tables or graphs

	A graph we could have created to help the analysis is making another visual that compares all the subcategories under the parent category “theater”. There are only three (plays, spaces, and musicals). Comparing how their launch date also affects their outcomes could also help reassure the patterns between successful or failed fundraising campaigns. Another table that could be created is a pivot chart similar to the one we created in “Theater Outcomes by Launch Date” but filter by country to see the patterns between each country.
