---
title: "Creating Reports"
parent: "Introduction to SimplyAnalytics"
layout: "home"
created_date: 2018-01-04
maintainer:
    - name: Leanne Trimble
      link: https://library.utoronto.ca/staff/leanne-trimble
nav_order: 6
---
## Creating Reports
{: #creating-reports}


This part will be broken up into three sections, along with two Exercises:

[a) Creating a Business Report](#a-creating-a-business-report)

[EXERCISE 3](#exercise-3)

[b) Creating a Comparative Report](#b-creating-a-comparison-report)

[c) Creating a Ranking Report](#c-creating-aranking-report)

[EXERCISE 4](#exercise-4)

---------------------------------------------

### A) Creating a Business Report

A businesses report view was already created when we started adding businesses to our map. Click on it now from the views bar.

The businesses report will appear. Along the top of the report, you can choose the businesses search you wish to display in your report. If your “Hardware stores, sales volume >$5m” search is not selected, choose it now. The location should be set to Toronto CMA, though this can be changed as well from the drop-down menu.

<img src='{{ '/assets/images/063-business-report.PNG' | relative_url }}' alt='' title='' width='1134' height='558' />

The report itself appears in the main window. It contains a listing of all businesses that matched your search parameters, within your selected location. You can use the scroll bar at the bottom to look at additional columns in the report.

<img src='{{ '/assets/images/065-business-report3.PNG' | relative_url }}' alt='' title='' width='657' height='441' /> <img src='{{ '/assets/images/066-business-report4.PNG' | relative_url }}' alt='' title='' width='605' height='441' />

For those interested in mapping, note that this report includes the latitude and longitude for each business, so you could use this report in Geographic Information Systems (GIS) software.

Next, open the **View Actions** menu and choose **Columns**. Here you can see that there are additional columns available that are not displayed in the default report view. For example, we mentioned earlier that many businesses are tagged with multiple NAICS codes, a primary code and one or more secondary codes. You could see all the NAICS codes by adding check marks to them in this menu.

<img src='{{ '/assets/images/067-business-report5.PNG' | relative_url }}' alt='' title='' width='932' height='807' />

Note: not every business will have data for every available column. The default report view shows the columns that are most commonly populated.

Once you have configured the report columns, you can export the report. Click the **Export** button. Choose your “File format” and “Export to” options and click **Export**.

<img src='{{ '/assets/images/068-business-report6.PNG' | relative_url }}' alt='' title='' width='331' height='290' />

You do not always need to start in a map view to create a businesses report. You can create a new businesses report at any time by clicking **New View**.

<img src='{{ '/assets/images/069-new-view.PNG' | relative_url }}' alt='' title='' width='115' height='537' />

The “New View” screen appears. Under “Business Table”, select **Create**.

<img src='{{ '/assets/images/070-new-view2.PNG' | relative_url }}' alt='' title='' width='824' height='669' />

The setup screen for your new businesses report appears. Here you will be able to select any location and business search you have done in the past, or you can run new searches using the side panel and the results will immediately become options in your setup screen. When you have made your selections, click **Done**.

<img src='{{ '/assets/images/071-new-view3.PNG' | relative_url }}' alt='' title='' width='833' height='516' />

Your business report appears. You can continue to modify the report at any time by running new searches for businesses or places in the side panel. These will immediately become available in the drop-down menus at the top of your report.

 

### EXERCISE 3
{: #exercise-3}

***Task: Using the Businesses 2 report view, generate a businesses report. Give the report a new name, and export it to a file.***

Take the time to play around with the different columns available. Open up your exported file and have a look at it.

 

### B) Creating a Comparison Report

The comparison report will let you create a table comparing several locations and/or several variables. Every new project has one comparison report view included by default. Click **Comparison Report** on the views bar. (Note: you can always create more comparison reports by clicking New View). The basic comparison report appears.

<img src='{{ '/assets/images/072.0.png' | relative_url }}' alt='' title='' width='104' height='491' /> <img src='{{ '/assets/images/072-comparison-report.PNG' | relative_url }}' alt='' title='' width='415' height='417' />

Your default view may differ slightly, but in general it will display one or more variables and locations. To configure this, open the **View Actions** menu and select **Edit View**.

<img src='{{ '/assets/images/073-comparison-report2.PNG' | relative_url }}' alt='' title='' width='317' height='280' />

Here you can choose which locations and variables to display. You can select as many of each as you like. You can also add any new locations and variables by running searches in the side panel. We will now create a report to compare the percentage of mandarin speakers in the Toronto and Hamilton CMAs. To begin, go to Locations and add Hamilton to your selection.

<img src='{{ '/assets/images/074-comparison-report3.PNG' | relative_url }}' alt='' title='' width='334' height='203' />

Next we need to search for a new variable. Select the **Data** tab on the side panel. This time instead of browsing by category or dataset, we’ll run a search. Type **mandarin** in the search box and hit **Enter**. The search results will appear.

<img src='{{ '/assets/images/075-search-data.PNG' | relative_url }}' alt='' title='' width='1043' height='652' />

We can see from looking at the results that we could use data for “mother tongue” or “language spoken most often at home”. Let’s use “mother tongue”. For the **% Household Population by Mother Tongue** variable, select the **More options** button and choose **Use this Data Variable**.

<img src='{{ '/assets/images/076-search-data2.PNG' | relative_url }}' alt='' title='' width='448' height='398' />

Close the search window by clicking on the **X** in the top right-hand corner. Our new variable has now been added to the “Edit Comparison Report” window. **Un-select all other variables**, leaving only the mandarin speakers variable selected. Click **Done**.

<img src='{{ '/assets/images/077-comparison-report4.PNG' | relative_url }}' alt='' title='' width='661' height='574' />

You don’t necessarily have to be in “Edit Comparison Report” mode to add variables to the report. Let’s add the percentage of Cantonese speakers to the report as well. On the **Data** tab in the side panel, search for **cantonese** and add the % Household Population by Mother Tongue variable (by selecting **Use this data variable** from the options). Close the search results window. This variable is now included in the report.

<img src='{{ '/assets/images/078-comparison-report5.PNG' | relative_url }}' alt='' title='' width='524' height='319' />

At any time, you can remove a variable from the report by clicking on it, and choosing **Remove from this Report** from the pop up menu.

<img src='{{ '/assets/images/SimplyAnalytics_081.png' | relative_url }}' alt='More options for selected dataset in report' title='' width='573' height='520' />

When you click on a location, a pop up menu also appears, which will let you hide the location and will also give you some sorting options. Click on **Hamilton**, then choose **Sort, smallest to largest**.

<img src='{{ '/assets/images/080-comparison-report7.PNG' | relative_url }}' alt='' title='' width='526' height='418' />

The order the data variables are listed will change so that the one with the smallest value in Hamilton will be listed first.

Finally, just like with the previous report, you can rename it and export it if you desire.

 

### C) Creating a Ranking Report

The ranking report will let you create a table view and compare data for all geographic units within a location, ranking them by your chosen variable. Every new project has one ranking report view included by default. Click **Ranking** on the views bar. (Note: you can always create more ranking reports by clicking New View). The basic ranking report appears.

<img src='{{ '/assets/images/081-ranking-report.PNG' | relative_url }}' alt='' title='' width='107' height='497' /> <img src='{{ '/assets/images/082-ranking-report2.PNG' | relative_url }}' alt='' title='' width='959' height='498' />

This report is displaying the census divisions within the Toronto CMA. It is displaying three variables by default, and sorting the table based on one of these variables (total population). Your default view may differ from the screenshot depending on what locations and variables you have used in your map.

***Task: Create a report to compare the expenditures on food and women’s clothing for all census subdivisions (municipalities) in both the Toronto and Hamilton CMAs.***

We can set up some of these parameters immediately using the drop-down menus at the top of the screen. Change census divisions to census subdivisions. Change Toronto to the combination location we created earlier for Toronto & Hamilton CMAs. (As with all reports, you could search for new locations and create new custom locations using the Locations tab in the side panel at any time, and these would be added to your options list.)

<img src='{{ '/assets/images/083-ranking-report3.PNG' | relative_url }}' alt='' title='' width='671' height='258' />

Now we need to add our variables. In the **Data** tab on the side panel, choose the **Consumer Behaviour** category. In the search box, scroll down in the central panel until you find the date limit options. The default option is always going to be to give you the latest available data. In this case, the latest available is 2017. Because the year 2017 is not yet over, we know that these data must be projections. If we want to use the most recent year for which complete data is available, we can select **2016**.

<img src='{{ '/assets/images/084a-browse-filter.PNG' | relative_url }}' alt='' title='' width='351' height='586' />

Now, to select the variable, let’s use the filter option. Type food in the filter box. Add the Average Total Expenditure \| Food variable to the table.

<img src='{{ '/assets/images/084-browse-filter.PNG' | relative_url }}' alt='' title='' width='1044' height='770' />

Next, change the filter term to **clothing**. Add the variable Average Total expenditure \| Clothing \| Women’s and girls’ clothing (4 years and over) \| Women (aged 15 and over): Clothing to the map.

<img src='{{ '/assets/images/085-browse-filter2.PNG' | relative_url }}' alt='' title='' width='1046' height='812' />

Remove the variables we don’t want from the table. One way to do this is to click on the name of a variable and choose **Hide Data Variable from this Report**.

<img src='{{ '/assets/images/086-ranking-report4.PNG' | relative_url }}' alt='' title='' width='503' height='269' />

Another way is to go to the **View Actions** menu and choose **Edit View**.

<img src='{{ '/assets/images/087-ranking-report5.PNG' | relative_url }}' alt='' title='' width='264' height='207' />

In the “Edit View” options you can **unselect** everything you don’t want to include in your table. Click **Done** when you are finished.

<img src='{{ '/assets/images/088-ranking-report6.PNG' | relative_url }}' alt='' title='' width='922' height='760' />

Your report will now display. You can see the average spending on both food and women’s clothing

<img src='{{ '/assets/images/089-ranking-report7.PNG' | relative_url }}' alt='' title='' width='716' height='532' />

You can reverse the order of the columns by clicking and dragging them.

<img src='{{ '/assets/images/090-ranking-report8.PNG' | relative_url }}' alt='' title='' width='712' height='466' />

You can change which column the table is sorted by, by clicking on a column and choosing **Sort, largest to smallest**.

<img src='{{ '/assets/images/091-ranking-report9.PNG' | relative_url }}' alt='' title='' width='696' height='298' />

Let’s make one further change. Let’s only show the census subdivisions (municipalities) where the expenditure on food is more than $12,000 on average annually. Click the **Filtering** button.  In step 1, click on the **average expenditure for food variable**. This variable will now appear in step 2.  Add the expression **is greater than $12,000**.  Select **Hide** instead of Strikeout. Click **Apply**, then close the filtering window.

<img src='{{ '/assets/images/092-filtering.PNG' | relative_url }}' alt='' title='' width='926' height='731' />

Now only census subdivisions with average spending on food of more than $12,000 are displayed. Notice that the word “on” appears on the Filtering button to remind you of the filter you have set. You can remove the filter at any time by clicking on Filtering again and changing the filter toggle from On to Off.

<img src='{{ '/assets/images/093-filtering2.PNG' | relative_url }}' alt='' title='' width='348' height='242' />

Finally, just like with the previous report, you can rename it and export it if you desire.

 

 

### EXERCISE 4
{: #exercise-4}

***Task: Explore the different reports. You can make any of the report types covered in this workshop, or go to New View and explore additional report options available in SimplyAnalytics.***

**Technique:** [Data Visualization](https://mdlutoronto.github.io/tutorials-search/?technique=Data+Visualization), [Searching for maps and data](https://mdlutoronto.github.io/tutorials-search/?technique=Searching+for+maps+and+data) \| **Tools:** [SimplyAnalytics](https://mdlutoronto.github.io/tutorials-search/?tool=SimplyAnalytics) \| **Data Format:** [Statistics](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Statistics), [Vector](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Vector)
