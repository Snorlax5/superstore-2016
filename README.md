#### Superstore 2016 
# https://app.powerbi.com/groups/me/reports/92832fb1-1d5c-4cdc-bee3-52b0d82b97e6/ReportSection
 
I imported the superstore 2016 xlxs into powerbi.<br />
I created new table called DateTime and inserted function <br />
DateTime = ADDCOLUMNS(CALENDAR(MIN(Orders[Order Date]), MAX(Orders[Order Date])), "Day", DAY([Date]), "Month", FORMAT([Date],"MMM"), "Year", FORMAT([Date],"YYYY"))<br/>
For defining date month year from order date
I added New column called deliver days 
Deliver Days = DATEDIFF( Orders[Order Date],Orders[Ship Date],DAY)<br />


After that I inserted textbox and Write that Superstore and sales analysis  for just heading purpose<br /><br />
I inserted few cards  from visualization in dash board and format that cards like changing the background opacity and color of fonts to white<br />
1)Salesc<br />
2)Profit <br />
3)Quality <br />
Then I added two slicer for order date and ship date and also change their backgground opacity to 100 and resize the boxes to set to the dashboard.
Then I added map visualization and  put stare in location and put country in legend and format it like map setting I choose dark and choose title off and tooltips on for the map.<br />
Then I added donut chart and put segment in legend and sales in values and also formatted this by background transparency 100 and title to mid and tooltip on.
Then I added Pie chart and put region in legend and sales in values and also formatted this by background transparency 100 and title to mid and tooltip on.
Now I wanted some different type of visualization so I went to more visualization  ans explore there.<br />
I found 2 interesting  sunburst visualization and scroller visualization so I downloaded that.<br />
In sunburst , you can add groups like category and subcategory for visualization and put values in sales. And format  the visualization like transparent background and title to centre <br />
After that I inserted scroller and explore the scroller . I liked it because it is auto scrolling and its like we can see it in share market in scroller I put Subcategory to category and sales to absolute value but it didn’t give me green or red markers so I change sales to measure deviation
After that I set dashboard and format canvas background to black and change some graphs font colour because it was to good at visualizing 
After that I inserted textbox and Write that Superstore | Profit analysis  for just heading purpose<br />

Now I inserted a new page and rename it to profit analysis. I inserted few cards  from visualization in dash board and format that cards like changing the background opacity and color of fonts to white. <br />
1)Sales <br />
2)Profit <br />
3)Quality <br />
After that I added slicer for selecting individual states. <br />
And added data table for subcategory and region to columns and profits to the value. Now we can select subcategory region vies for profit <br />
Now I added 3 donut charts for profit for region , segment, category for visualization and format that  according to previous one. <br />
Then I added stacked bar chart for profit for subcategory and formatted . <br />
I want line graph for year wise profit so I added line chart and in axis I added order date and profit in values. And I formatted this little bit and I explore that there is one option called  drill down and  I got the chart year and quarter wise profit. <br />
I inserted scroller to category wise profit and make some adjustment  to the canvas and settle it. <br />











 
