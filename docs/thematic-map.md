---
title: "Creating a Thematic Map"
parent: "Introduction to SimplyAnalytics"
layout: "home"
created_date: 2018-01-04
maintainer:
    - name: Leanne Trimble
      link: https://library.utoronto.ca/staff/leanne-trimble
nav_order: 3
---
## Creating a Thematic Map
{: #creating-a-thematic-map}

This section will bring you through a number of the functions available on SimplyAnlaytics, with the ultimate goal of *making a map of average houshold income by sensus subdivisions within the Toronto CMA*. Our work will be broken up according to the development of the following skills:

[a) Navigating and Exploring the Map](#a-navigating-and-exploring-the-map)

[b) Selecting a Variable](#b-selecting-a-variable)

[c) Refining the Location](#c-refining-the-location)

[d) Legend Editor](#d-legend-editor)

[e) Map Management](#e-map-management)

-------------------------------------

### A) Navigating and Exploring the Map

Use the map toolbar to navigate and explore the map you have created.

<img src='{{ '/assets/images/098-CLAREExploring.png' | relative_url }}' alt='' title='' width='721' height='451' />

Click the “**i**” icon to activate “information” mode. **Click on any census subdivision** on the map. The information window will appear, telling you the name of the census subdivision as well as the total population for that location (or whatever other information you are mapping: population is generally the default having made a new project). Notice you can also add any individual location showing on a map to a new project, or to your favourites list. You could also give this location a custom name if you wished, using the “Add alias location name” option. When you have finished looking at the details, **close the information window**.

<img src='{{ '/assets/images/099-EXTRAinfoicon_0.png' | relative_url }}' alt='' title='' width='648' height='526' />

### B) Selecting a Variable

Notice the panel at the left side of the screen. It has three tabs, “Locations”, “Data” and “Businesses”. Select the **Data** tab if it is not already selected.

The individual data characteristics that you can include on your map are known as “variables”. Various categories of variables are listed in the Data tab. Click on **Income**. The variable selection panel appears.

<img src='{{ '/assets/images/SImplyAnalytics_01.png' | relative_url }}' alt='A list of data characteristics that can be included on your map.' title='' width='600' height='328' />

At the right-hand side of the panel is a list of possible variables to add to the map. There are quite a lot of them! There are variables that show the total number of individuals or households making a certain income range, as well as variables showing total, average, or median income. You can use the various filter options to narrow down your options if you like. For example, under “Data Type”, select **average**. The selection you have made appears at the top of the window as a blue box, which can be removed at any time if you change your mind.

<img src='{{ '/assets/images/012-var-selector2.PNG' | relative_url }}' alt='' title='' width='749' height='572' />

Let’s take a closer look at the third variable in the list, “Households by Income (Current Year) \| Average Household Income (Current Year $)”. You can find out more about this variable by clicking the menu button (vertical ellipsis) and choosing **View Metadata**.

<img src='{{ '/assets/images/012-var-selector3.png' | relative_url }}' alt='' title='' width='749' height='572' />

The “Variable Metadata” window appears. Here you can find out some additional details about this variable. We can see that it is an estimate variable for the current year (2017) and that it comes from an organization called Environics. So, we have determined that this data is not official census data from Statistics Canada. That doesn’t mean it is bad, it is simply important to be aware of your data sources, and to cite them correctly when you use them in your academic work.

<img src='{{ '/assets/images/014-view-metadata.PNG' | relative_url }}' alt='' title='' width='664' height='479' />

Close the metadata window when you have finished reviewing the information.

Click on the vertical ellipsis for our variable of interest again and select Use this Data Variable. Notice that the variable now has a check mark on it. You can add as many variables as you like at once, and later you will be able to toggle which one is shown on the map. For now we will just add the average income variable.

<img src='{{ '/assets/images/016-var-selector5.PNG' | relative_url }}' alt='' title='' width='620' height='602' /> <img src='{{ '/assets/images/017-var-selector6.PNG' | relative_url }}' alt='' title='' width='592' height='601' />

One final thing before we close this window.  Click on the menu button for our variable of interest again and select **Add to Favorites**.

<img src='{{ '/assets/images/015-var-selector4.PNG' | relative_url }}' alt='' title='' width='732' height='695' />

You can add any variable to your favourites list in order to find it again easily in the future. Keep in mind however that if you signed in as guest, the selection will not actually be saved for next time.

Now close the variable selection panel. In the data panel, you can click on the star icon and all the variables you have favourited will be available.

<img src='{{ '/assets/images/018-favorites.PNG' | relative_url }}' alt='' title='' width='303' height='462' />

Now have a look at your map. Notice that the variable being displayed is now the household income variable. Click on the drop-down menu. At any time, you can choose amongst all the variables that have been added to this map. Right now, we have the three default variables SimplyAnalytics always adds, plus our household income variable. Leave the income variable selected.

<img src='{{ '/assets/images/019-variables.PNG' | relative_url }}' alt='' title='' width='782' height='427' />

### C) Refining the Location

We’ve already chosen to create our map of the Toronto CMA. However, right now the map is showing CMA broken down by Census Divisions. We want to show Census Subdivisions. Click on the drop-down menu for Census Divisions, and change the selection to **Census Subdivisions** instead.

<img src='{{ '/assets/images/020-change-geo-breakdown.PNG' | relative_url }}' alt='' title='' width='702' height='292' />

The map will refresh and now the light grey boundaries will show smaller regions which correspond to municipalities. Some select municipalities will be labelled.

Note also that you can change your overall geography at any time by selecting the **Locations** tab in the left-hand panel. You can search for a new location there. For example, search for **Hamilton**. Click the **CMA option** for Hamilton.

<img src='{{ '/assets/images/021-change-geo-map.PNG' | relative_url }}' alt='' title='' width='304' height='279' />

Your map will now show Hamilton instead.  Now, in the drop-down menu above the map, you can choose between the Toronto and Hamilton CMAs at any time.

<img src='{{ '/assets/images/022-change-geo-map2.PNG' | relative_url }}' alt='' title='' width='537' height='323' />

You also have several options for creating custom locations. Let’s imagine that your research area actually includes both the Toronto and Hamilton CMAs and you want to map them both at the same time. On the Locations tab, click **Custom Locations**, then **Create new combination location**.

<img src='{{ '/assets/images/023-combination-location.PNG' | relative_url }}' alt='' title='' width='301' height='422' />

The “Create Combination Location” window appears. In step 1, give your custom combination location a **name**. In step 2, search for Toronto and Hamilton and **add each CMA to the list**. When your settings match the screenshot below, click **Save**.

<img src='{{ '/assets/images/024-combination-location2.PNG' | relative_url }}' alt='' title='' width='811' height='602' />

The combination location will appear on the map, outlined in yellow. In the drop-down menu at the top of the screen, this location will now also be available.

<img src='{{ '/assets/images/025-combination-location3.PNG' | relative_url }}' alt='' title='' width='561' height='631' />

Another custom location option is to create a radius location. This can be used to create a radius of a specified distance around a location. This is often used for small geographies. For example, imagine you wanted to study the neighbourhoods near the University of Toronto campus. You could create a radius location of 2km from the centre of campus to delineate your study area. Let’s create this now. In the Location tab, select **Create new radius location**.

<img src='{{ '/assets/images/026-radius-location.PNG' | relative_url }}' alt='' title='' width='305' height='393' />

The ”Create Radius Location” window appears. Let’s try to pinpoint the centre of campus as closely as we can by searching for the postal code of the downtown campus, **M5S 1A5**. Notice that the search results suggest a dissemination area, DA4157. Dissemination area is the most detailed census geography that we can map data for. You can search for postal codes in SimplyAnalytics, and the system will map them to the dissemination area in which they fall. This is handy because, while postal codes are often familiar to us, we rarely know dissemination area codes off the top of our heads! Click on the suggested dissemination area to select it.

<img src='{{ '/assets/images/027-radius-location2.PNG' | relative_url }}' alt='' title='' width='457' height='226' />

Next set the radius to **2 kilometres**, and name the location **University of Toronto area**. Click **Save**.

<img src='{{ '/assets/images/028-radius-location3.PNG' | relative_url }}' alt='' title='' width='457' height='477' />

The new radius location is added to your map. The original dissemination area is highlighted in yellow, and the 2km radius is highlighted in orange. If this is rather difficult to see on your screen, try **zooming out once** using the zoom slider on the map (or your mouse’s scroll wheel).

<img src='{{ '/assets/images/029-radius-location4.PNG' | relative_url }}' alt='' title='' width='553' height='566' />

At any time, you can view all your custom locations from the Locations tab, by clicking on **View your custom locations**.

<img src='{{ '/assets/images/030-custom-locations.PNG' | relative_url }}' alt='' title='' width='613' height='392' />

You can also save any location you have recently used to your favourites list. On the Locations tab, click the Recent Locations button (clock icon). The list of all your recently used locations appears. Click the **More options** button (three dots icon) for Toronto, then choose **Add to Favorites**. Close the Recent Locations menu.

<img src='{{ '/assets/images/030_2-favourite-locations.PNG' | relative_url }}' alt='' title='' width='519' height='406' />

Notice that now a star icon has appeared beside the recent locations icon. **Click it**, and you will see Toronto is now listed as a favourite location. You can do this for any location you think you would like to access again later without searching for it again. Favourites are available across projects.

<img src='{{ '/assets/images/030_3-favourite-locations2.PNG' | relative_url }}' alt='' title='' width='304' height='276' />

Let’s go back to the Toronto CMA to continue designing our map. Choose Toronto from the drop-down menu at the top of your map. Make sure Census Subdivisions is still selected as the geographic breakdown.

### D) Legend Editor

This map isn’t really very interesting. Almost the entire CMA is displayed as one colour! You can make some changes in the legend to display the data more clearly. On the legend in the top right-hand corner of the map, click **Edit**.

<img src='{{ '/assets/images/031-legend.PNG' | relative_url }}' alt='' title='' width='250' height='443' />

The Legend switches to edit mode. Change the classification method to **Quantiles (Local)**. Notice how the income ranges get adjusted and the map now depicts the differences between the CSDs more clearly. You can also explore the other classification methods if you desire.

<img src='{{ '/assets/images/032-legend-classification.PNG' | relative_url }}' alt='' title='' width='254' height='239' />

If you like, you can change your map’s colour scheme. If you’re finding it difficult to see the grey outlines of the Census Subdivisions, you could make their outlines thicker (e.g. change the thickness to 2). You could change the outline colour if you like as well.

<img src='{{ '/assets/images/033-legend-colour-scheme.PNG' | relative_url }}' alt='' title='' width='249' height='416' /><img src='{{ '/assets/images/034-legend-outline.PNG' | relative_url }}' alt='' title='' width='277' height='416' />

When you’re finished editing the legend, click **Done**. Your map may look something like the screenshot below.

<img src='{{ '/assets/images/034_2-edited_map.PNG' | relative_url }}' alt='' title='' width='864' height='641' />

### E) Map Management

There is no need to save the maps you create in SimplyAnalytics – they are saved automatically and appear within your project as “views” listed down the right-hand side of the screen. We have been working on the listing currently called “Map”. (We’ll be looking at the comparison reports and rankings a bit later). Click on the **tiny arrow** at the top left-hand corner of the Map listing, and select **Rename**.

<img src='{{ '/assets/images/037-views.PNG' | relative_url }}' alt='' title='' width='524' height='551' />

Give your map a **more descriptive name**. Hit **Enter** when you’re done typing to save the new name.

<img src='{{ '/assets/images/038-rename-map.PNG' | relative_url }}' alt='' title='' width='428' height='169' />

You can have as many maps as you wish within a project. Let’s create a new map now which we will work with in the next section. Click the New View button.

<img src='{{ '/assets/images/039-new-view.PNG' | relative_url }}' alt='' title='' width='351' height='415' />

The “New View” window appears. In the “Map” box, click **Create**.

<img src='{{ '/assets/images/040-new-view2.PNG' | relative_url }}' alt='' title='' width='968' height='635' />

You will be presented with a page called "Edit Map," where you can select which location, data, or businesses you would like presented in this map view. Press "Done" once you have made your selections.

<img src='{{ '/assets/images/101-new-map-selection.png' | relative_url }}' alt='' title='' width='975' height='416' />

You can then rename this map view to “Exercises” in the same way as your renamed our first map.

<img src='{{ '/assets/images/041-new-view-rename.PNG' | relative_url }}' alt='' title='' width='416' height='403' />

Finally, click on **Project Settings** at the top of the screen. Here, you will be shown a summary of all the settings in your project. You can remove, edit and rearrange your project as you desire. For example, let’s say we know we are no longer planning to work with the University of Toronto custom area in this project. Choose the **Remove Locations, Data, or Businesses** subtitle, click the “**x**” to remove it. It will still be available in other projects you might create in the future.

 

<img src='{{ '/assets/images/SimplyAnalytics_046.png' | relative_url }}' alt='Project Settings page for SimplyAnalytics' title='' width='994' height='314' />

### EXERCISE 1
{: #exercise-1}

SimplyAnalytics contains much more than the income variable we looked at in the first task. Take this opportunity to explore the Data tab to find variables of interest to your research.

***Task: Map a variable of your choice, this time showing census tracts within the City of Toronto (Census Subdivision).***

Click on the map we created named **Exercises**. This is where you will create your own map.

In the **Data** tab, take a closer look through the different categories of variables. When selecting a variable, choose “View Metadata” first and read the information provided about the data.

You can also choose to browse the variables by data folder rather than by category. Click the **Data Folder** to browse datasets in folders.

<img src='{{ '/assets/images/SimplyAnalytics_047.png' | relative_url }}' alt='Browse data in by data folder' title='' width='396' height='524' />

The listing of datasets appears. You can see there are datasets about health, spending, daytime population (i.e. place of work data) and more.

<img src='{{ '/assets/images/044-datasets.PNG' | relative_url }}' alt='' title='' width='298' height='589' />

To learn more about the different datasets and data providers contained in SimplyAnalytics, go the **Support** menu and choose **Data Documentation**.

<img src='{{ '/assets/images/045-data-documentation.PNG' | relative_url }}' alt='' title='' width='410' height='336' />

The “Data Documentation” window appears. This describes the data sources for both the Canadian and US variables in SimplyAnalytics. You can look at even more detail by clicking on the complete variable list for SimplyAnalytics Canada.

<img src='{{ '/assets/images/046-data-documentation2.PNG' | relative_url }}' alt='' title='' width='998' height='771' />

Take some time to explore the full range of variables and create a map showing a variable by census tracts within the City of Toronto (Census subdivision). Here is an example of what your map might look like. Remember that your map’s distribution will differ depending on the variable you chose.

<img src='{{ '/assets/images/047-example-map.PNG' | relative_url }}' alt='' title='' width='1029' height='703' />

**Technique:** [Data Visualization](https://mdlutoronto.github.io/tutorials-search/?technique=Data+Visualization), [Searching for maps and data](https://mdlutoronto.github.io/tutorials-search/?technique=Searching+for+maps+and+data) \| **Tools:** [SimplyAnalytics](https://mdlutoronto.github.io/tutorials-search/?tool=SimplyAnalytics) \| **Data Format:** [Statistics](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Statistics), [Vector](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Vector)
