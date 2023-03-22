# Tableau Dashboards - Cumulative Lab

## Introduction
We have used the Superstore Sales dataset learn about the Tableau environment interface, including the Start page, Data Source page, and Workspace. Then, we explored the useful visualizations that can be created in Tableau Public. Finally, we discussed how we can combine the vizzes in our workbooks to create dashboards to communicate our insights.  Now it's your turn to apply your skills in Tableau.

In this exercise, you will use knowledge of the Tableau interface, data visualizations, and dashboards to create the Super Store Sales dashboard.

To recreate the dashboard, follow the instructions below. When you are finished, save and publish to Tableau Public. Then, add the link to this assignment and click submit. You've just created your first interactive dashboard with Tableau Public!

## Instructions

### Part A - Connect to a Data Source and Create a New Workbook
1. Launch Tableau and from the Start page, use the Connect pane to open the SuperStore Sales dataset.
2. From the Data Source page, populate Canvas logical layer with the `Orders` table and the `People` table.
    
    
### Part B - Create a Bar Chart
1. Create a new worksheet.
2. Drag the `Profits` pill to the Columns shelf from the Data Pane.
3. Drag the `Sub-Category` pill to the Rows shelf from the Data Pane.
4. Change the title of the chart to "Profits by Sub-Category". Change the font size to 16.  Center the title and change the background to light-gray.
5. Then, order the bars in the bar chart in descending order.
6. Next, use the Marks card to change the color of the bars to "Sunrise-Sunset Diverging"
7. Next, use the Marks card to add labels that indicate the sum of the profits for each of the bars. (Don't forget the currency symbols!)
8. Fit the visualization to "Entire View".


### Part C - Create a Line Chart
1. Create a new worksheet.
2. Drag the `Order Date` pill to the Columns shelf from the Data Pane. Adjust `Order Date` to "Quarterly".
2. Drag the `Sales` pill to the Rows shelf from the Data Pane.
3. Change the title of the chart to "Quarterly Sales by Region". Change the font size to 16.  Center the title and change the background to light-gray.
4. Then, use the Color attribute on the Marks card to create distinct lines for each Regional Manager.
6. Next, use the Marks card to add the total sales for each quarter to the chart. (Don't forget the currency symbols!)
8. Fit the visualization to "Entire View".


### Part D - Create a Regional Map
1. Create a new worksheet.
2. Drag the `Longitude` and `Latitude` to the Row shelf and the Column shelf.
3. Change the title of the chart to "Sales by Regional Manager". Change the font size to 16.  Center the title and change the background to light-gray.
4. Add `Sales` to the Marks card, and select the Size attribute. Then, add `Postal Code` to the Marks card and select the Detail attribute. This will populate the map with sales by postal code.
5. Add `Regional Manager` to the Marks card, and select the Color attribute. Then, click the Color icon and select Edit Color. Then, select Lightening Default. Assign the following colors to each Regional Manager:
    
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/regional-mgr.png" alt="This is the alt-text for the image." style="width: 800px;"/>
</td></tr></table>
    </center>
</div>

6. Next, drag  `Profit` to the Marks card and add the Detail attribute. 
7. Then, drag `Regional Manager` to the Filter shelf.


### Part E - Create a Time Series Line Graph
1. Create a new worksheet.
2. Drag the `Longitude` and `Latitude` to the Row shelf and the Column shelf.
3. Change the title of the chart to "Quarterly Sales by Regional Manager". Change the font size to 16.  Center the title and change the background to light-gray.

### Part F - Create and Publish the Dashboard
1. Adjust the layout from **Phone** to **Desktop**. Select **Fit Width** and set **Height** to 1060px. Then, select **Custom** and **Tiled** from the layout card.
2. Check **Show Dashboard Title** and change the title to "Super Store Sales Dashboard". Change the font size to 22. Center the title and change the background to light-blue.
3. Add a **Horizontal Container** under the dashboard title and set the layout to **Tiled**. 
4. On the legends, change the font size to 12, and center the title.
5. Using two **Vertical Containers**, position the charts and legends in the layout displayed below.

<br>
<br>
<div>
    <center>
<table><tr><td>
<img src="https://curriculum-content.s3.amazonaws.com/data-science/images/v3/tableau/tableau/new-dash.png" alt="This is the alt-text for the image." style="width: 800px;"/>
</td></tr></table>
    </center>
</div>

6. Save and publish to Tableau Public as `learn-wb-MMDDYY-XX` where `XX` is your initials and `MMDDYY` refers to the current month, date, and year.
7. Locate the share link on your Tableau Public site and upload it to this assignment.
