# Tableau Dashboards - Cumulative Lab

## Introduction
Over the course of the Tableau module, we have used the Superstore Sales data set learn about the Tableau environment interface, including the Start page, Data Source page, and Workspace. Then, we explored the useful visualizations that can be created in Tableau Public. Finally, we discussed how we can combine the vizzes in our workbooks to create dashboards to communicate our insights.  Now it's your turn to apply your skills in Tableau.

In this exercise, you will use knowledge of the Tableau interface, data visualizations, and dashboards to re-create the dashboard pictured below. To simplify the process, we have labeled each section of the dashboard with a number.

Follow the prompts for each numbered section to recreate the dashboard.

<div>
    <center>
<table><tr><td>
<img src = "https://curriculum-content.s3.amazonaws.com/data-science/images/images/tableau/dashboards/tab-dash-labeled.png" alt="This is the alt-text for the image." style="width: 700px;"/>
</td></tr></table>
    </center>
</div>

### 1. Create a New Dashboard in `learn-wb`
1. Open up `learn-wb-YYYY-MM-XX` from Tableau Public.
2. Use the sheets tab to create a new dashboard. Change the name on the tab on the sheets tab to "Super Store Sales Dashboard".
3. Then use the Dashboard pane to set the Device Type to Desktop. Set the width to __Fit All__. Then, select __Floating__ for the layout. 
4. You should see the names of the worksheets we created previously in the Dashboard pane. 

### 2. Sales by Region Plot
Drag and drop the `Region` sheet onto the dashboard. Enter the visualization and ensure the following:
* Regional Manager is indicated by color
* Sales are indicated by size
* Make this plot a filter so the user can filter the rest of the dashboard by region using this viz.
    
### 3. Quarterly Sales by Region Plot
Drag and drop the `Sales` plot onto the dashboard. Enter the visualization and ensure the following:
* The x-axis is changed from `Monthly` to quarterly
* Regional Manager Name and Region are both shown on the legend
* Sales amounts are labeled on the plot

### 4. Orders by Region Plot
* `Orders (COUNT)` is sub-divided by `Category`

### 5. Profits by Sub-Category
* Negative amounts are in red, and positive amounts are in green `Profit`
* Profit amounts in labels are rounded to the nearest dollar

When you are finished, save and publish to Tableau Public. You've just perfected your first interactive dashboard with Tableau!
