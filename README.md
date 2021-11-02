# Kickstarter-Challenge
## Overview of Project

The focus of this project was to use the provided dataset to visualize outcomes based on launch dates and goals. 

## Analysis and Challenges

The first task was to set up a new column and parse the year from the Date Created Conversion column. That was done by using the `YEAR()` formula within Excel. Then moved on to creating a pivot table filtering the data by the Parent Category Theater and all years. The columns were the outcome statuses while the rows were organized by the month they were created. Once the pivot table was set a line chart was created to visualize the findings in the chart below.

![Theater Outcomes Based on Launch Date](https://github.com/racruz25/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

The second assignment asked an illustration of the outcomes of plays based on the goal amount. Beginning with a new spreadsheet, columns displayed the number of each outcome and the percentage of total outcome for the row that that was broken down in to various increments. To find the number of successful, failed, and canceled outcomes a `COUNTIFS()` statement was needed. Counting the number of each outcome based on the range of the goal for each row. Then using `SUM()` to find the total number of project for each goal interval. The last step was finding the percentage of the total projects each outcome had per goal range. Once completed the chart below was created.

![Outcomes Based on Goal](https://github.com/racruz25/kickstarter-analysis/blob/main/Resources/Outcomes_vs_Goals.png)

## Results
Two conclusions drawn in Theater  is apparent that there is mostly a rise in successful campaigns that peaks in May and trends downward through the remainder of the year. Also that number of failed campaigns stays someone consistent throught the year.

Then with the care based on goals show that generally the lower the goal the more success rate campaigns have, outside of the $35,000 to $40,000 range.
Another chart for consideration would be the number of backers for each theater or play category may have painted the picture if there is a difference in the year or if there is an increase in backers based on goal. 

