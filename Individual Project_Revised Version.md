# Individual Project Revised Version

## Dashboard
![alt text](https://github.com/kwright76/Visualizations/blob/master/Revised%20Vers_Dash.JPG)

## Aspect #1
![alt text](https://github.com/kwright76/Visualizations/blob/master/Revised%20Vers_1.JPG)

### Documentation
In this aspect you can see the correlation between the amount of red light violations and speeding violations in the city of Chicago. Due to the closely correlated aspects of each line and not focusing on the values these lines are comprised of, it is shown that speeding violations rise and fall with the amount of redlight violations captured by the cameras. I have included a forecast of future trends based off this data. Although there is a continuing decline in overall traffic violations, there is not a substantial decrease to show that people are driving to make themselves and others safer on the roadways. 

### Creation
To create this chart, place violaiton date in the columns and sort it by month/year. Next select number of records from each data source and make sure to rename them to differentiate the two options. In the show me tab select the dual lines graph to combine the two measures from the rows selection. Lastly, apply the forecast selection for only the speeders aspect as this graph is meant to project statistics for speeding violaations and the red light data should only attribute the data. To add the finishing touches get rid of the row headers as the values are not necessary to magnify the point the visualization is trying to get across. 

### Changes
To improve on this visualization, I added the forecasting feature to show the future is not so bright for the safety of Chicago.

## Aspect #2
![alt text](https://github.com/kwright76/Visualizations/blob/master/Revised%20Vers_3.JPG)

### Documentation
This aspect shows the speeding violations in each Chicago neighborhood for each month and year by selecting the month and year on the sliding bar or dropdown menu. This is significant as it shows how a single neighborhood consistently has the most or one of the most violations month after month for a series of years. 

### Creation
To create this visualization first populate the rows with the number of speeders and the columns with the neighborhoods dimension. Add color and text marks for the amodunt of violations to show contrast and place the violation date dimension in pages. Make sure to filter the pages by month and year to be able to select specific time periods.

### Changes
To show granularity, I included a page selector for month and year.

## Aspect #3
![alt text](https://github.com/kwright76/Visualizations/blob/master/Revised%20Vers_2.JPG)

### Documentation
This aspect shows differences between the speeding violations in the north, south, east, and west segments of Chicago. It is noteworthy to point out the the number of violations in the past four years has not changed between the four segments and the west side of the city has substantially more violations than the other segments. 

### Creation
First to create this visualization the Address dimension needs to be split to pull out the N, E, S, and W from each street name. Then place the sum of records in rows, and the year and direction pulled out earlier in the columns. Change the color to show differentiation between the amounts and filter the outlying years to show complete years of data. Lastly, trend lines were added to show the 

### Changes
To improve this visualization I included the year distinction to compare the segments at a more granular level. From here I noticed there was not a change year over year so i also included the flat trend lines. 




## To Tableau Public Document
https://public.tableau.com/profile/kyle.wright#!/vizhome/IndividualProject_RevisedVersion/RevisedVersionDashboard
