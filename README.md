# kickstarter-analysis
## Overview of Project
Louise’s play Fever came close to its fundraising goal in a short amount of time. She wants to know how different campaigns fared in relation to their launch dates and their funding goals. Performing analysis on Kickstarter data to uncover trends
### Purpose
The purpose of this project is to develop outcomes of fundraisers based on their launch dates and funding goals. To achieve this, I used advanced formulas and terminologies, interactive charts and graphs with pivot tables and  to organize the data with filters and conditional formatting. The above mentioned skills allowed me to reveal trends which would help Louise.
## Analysis and Challenges
This project constitutes two main analysis.  The first is the Analysis of Outcomes Based on Launch Date and second, The Analysis of Outcomes based on Goals. Both analysis involved 
organizing, filtering, sorting and visualizing the data. Below gives a detailed description of both analysis.
### Analysis of Outcomes Based on Launch Date
With this challenge, I needed to ensure that I organize, sort, filter and visualize the data set to allow me read the trend based on outcomes on launch date. I did that by creating an additional column  called “Years” to the Kickstarter worksheet. The data for this column was derived from the use of the Year() function from the “ Date Created Conversion” column. This step would allow me to easily create a pivot table and chart. 

Since our analysis is focused on the launch dates of theater outcomes, I went ahead to filter the parent category to select only “Theater”.

Once I had organized, sorted and filtered the data, the next step was to visualize it. I completed this step by creating a line chart from the pivot table which I labelled Theater_Outcomes_vs_Launch.  I selected Pivot Table Analyze, Pivot Chart then Change Chart Type to Line Chart.  I added a title to the chart by selecting Add Chart Element and selected Chart Title.

From the graph, the successful outcomes varies throughout the months  with a high range of 111 and its lowest range of 37. The failed outcomes were more or less in the same range and not having extreme values. It has a lowest of 31 and highest 52. The canceled outcomes were more stable through the year. Seasonality seems to play a role in the outcomes.   
### Analysis of Outcomes Based on Goals
The Analysis of Outcomes Based on Goals involved determining the trend established by filtering on the Kickstarter “outcome” on the Goals amount column using specific ranges  and using plays as the criteria. This was made possible through the use of the COUNTIFS()function by counting the Number of Successful, Number of Failed and Number of Canceled which match the play criteria in the IF statement. 

To have a more organized and easier to read data, I used the SUM() function to populate the “Total Projects” column which helped in calculating the percentage of successful, failed and canceled projects for each row. 

The second phase of this analysis involved visualizing the organized and filtered data. I created a line chart to visualize the relationship between goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis. 

From the graph, the goal ranges less 10,000 had the most number of projects. Both the successful and failed projects within those ranges had the highest number of projects. 

### Challenges and Difficulties Encountered

I encountered some challenges on the second analysis “ Analysis of Outcomes Based on Goal”. The challenge had to do with the COUNTIFS() function. The challenge I encountered was a s a result of was not referencing/including the goal column from the Kickstarter worksheet. As a result, Excel was unable to read the function. 

A second challenge I faced had to do with the percentage function. For some reason, my  percentage results always came in 4 digits or more. An example is in Cell F2 I kept getting 7603%.
### Results
## What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion I can draw based on the analysis is that May and June had the highest successful outcomes 111 and 110 respectively.  

The chart/graph also shows that it is better to have an event within April – September to stand a chance of having a successful fundraising event. In addition, the number of successful and failed events in December are almost the same meaning December is really not the best time to hold events.

## What can you conclude about the Outcomes based on Goals?
The chart/graph shows that the higher the fundraising goal, the more likely the event will fail. In addition, the most successful goal that was reached is less than $1000

## What are some limitations of this dataset?
A limitation of this dataset is not knowing how many people pledged to a particular goal. It would be important to have an idea of the average number of individuals that pledge to a goal as averages are important in analysis. 

## What are some other possible tables and/or graphs that we could create?
It is possible to create a table and a bar graph that shows the years and how much was pledged to get a sense of which year had the most pledges. With that we can then further look into why a particular year had some outliers if any and what contributed to those outliers.
