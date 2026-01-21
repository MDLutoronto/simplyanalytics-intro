---
title: "Introduction to SimplyAnalytics"
layout: "home"
description: ""
permalink: "/"  #! Remove this if not the homepage
---

# Introduction to SimplyAnalytics

This online tutorial will provide an introduction to SimplyAnalytics and a few of its many possible uses. SimplyAnalytics is a web\-based data visualization application. It can be used to create simple thematic maps and tables from census and other socio\-demographic data, as well as business point data.

**Through the following** ***seven*** **steps, this tutorial will provide you with exercises interspersed to test your understanding:** 
  
[STEP 1: **Accessing** SimplyAnalytics](#Step1)  
[STEP 2: **Setting up a Project**](#Step2)  
[STEP 3: Creating **a Thematic Map**](#Step3)  
[**Exercise 1**](#Ex1)  
[STEP 4:Mapping **Business Locations**](#Step4)  
[Exercise 2](#Ex2)  
[STEP 5: **Options for Exporting** Maps](#Step5)  
[STEP 6: Creating **Reports**](#Step6)  
[Exercise 3](#Ex3)  
[Exercise 4](#Ex4)  
[STEP 7: **Getting Help**](#Step7)

Let's begin!

 

[STEP 1: **Accessing** SimplyAnalytics](#Step1)

All U of T students, staff, and faculty have access to SimplyAnalytics. SimplyAnalytics is accessed through a web browser (Firefox or Internet Explorer). If you are off\-campus, you need to login with your UTORid before you can use SimplyAnalytics. In this case, you should start by accessing SimplyAnalytics through the library’s website. Go to <https://mdl.library.utoronto.ca/>. Type “simplyanalytics” in the search box.  
  
<img src='{{ '/assets/images/simplyanalytics_1.png' | relative_url }}' alt='MDL library search bar' title='' width='600' height='164' />  
  
In the results, under “Geospatial Data”, click “SimplyAnalytics”:

<img src='{{ '/assets/images/SimplyAnalytics_002.png' | relative_url }}' alt='Result of searching SimplyAnalytics on MDL webpage' title='' width='596' height='300' />

On the SimplyAnalytics page, select the Index link:

 

<img src='{{ '/assets/images/SimplyAnalytics_003.png' | relative_url }}' alt='The SimplyAnalytics page on MDL website' title='' width='591' height='255' />

You will then be prompted to do one of the following: a) login with a previously\-registered email and password; b) sign in as a guest

<img src='{{ '/assets/images/simply1.JPG' | relative_url }}' alt='' title='' width='466' height='305' />

Create a new account, or login if you are a returning user. Alternatively, sign in as a guest, however, as stated on the sign\-on prompt, "guest" searches and work will not be saved. If you need to create a new account, you will need to sign in and then re\-access the account through the UofT portal. If you do not reacesss the sign in through the portal, the website will not realize your account is affiliated with a permitted partner. \\

Once you have logged in, you’ll see the SimplyAnalytics main screen. You may be offered a tour of the site, which briefly introduces you to its layout. Following this, if you are not immediately prompted to create a new project, click on **New Project** at the top of the screen to do so.

<img src='{{ '/assets/images/004-new-project.PNG' | relative_url }}' alt='' title='' width='1015' height='687' />

[STEP 2: **Setting up** a **Project**](#Step2)

In the “New Project” window, you first need to select a county. SimplyAnalytics contains data for Canada and the US, but you can only create a project for one country at a time. For your first project choose **Canada**.

You then need to focus the map on a particular area within Canada. Don’t worry, this can be changed at any time. It will simply provide your map’s initial view area. Type **Toronto** in the search box.

<img src='{{ '/assets/images/005-new-project2.PNG' | relative_url }}' alt='' title='' width='473' height='496' />

Notice that SimplyAnalytics makes several suggestions for Toronto. This is because there are several different geographic units used in the Canadian census, that have the name Toronto – there is a Toronto Census Metropolitan Area, a Toronto Census Division and a Toronto Census Subdivision. Have a look at the information box below (marked **ASIDE**) for details of what each of these mean. For this exercise, choose the Census Metro Area (which is the largest “version” of Toronto, including the city and its surrounding municipalities).

<img src='{{ '/assets/images/006-new-project3_0.PNG' | relative_url }}' alt='' title='' width='499' height='515' />

The Toronto CMA appears in a blue bar below the location search box. You could add additional locations to your project if you chose, but for now, let’s just use the one. Click **Next**.

A pop\-up window appears letting you know that SimplyAnalytics will include three basic census variables in your project by default. We will add additional variables in STEP 3; for now, select **Create project**.

<img src='{{ '/assets/images/007-basic-vars_0.PNG' | relative_url }}' alt='' title='' width='693' height='693' />

When you create a new project, the initial view is always a map, though you can also create a range of reports (which we will look at later). Notice in the toolbar at the top of the map, that by default the map is displaying the total population (most recent available year) in the Toronto CMA. The Toronto CMA is represented by the yellow outline on the map. Notice the third box in the toolbar that says “by Census Subdivision”. SimplyAnalytics will always show you your chosen map geography broken down by another, more granular level of geography. Census divisions are represented by the light grey lines on the map. All of the options in this toolbar can be adjusted, which we will do in the sections to come.

<img src='{{ '/assets/images/008-default-map.PNG' | relative_url }}' alt='' title='' width='966' height='589' />

Click on the name of your project at the top of the screen. Give your project a **new name** of your choice. Hit **Enter** to save the new name.

<img src='{{ '/assets/images/009-rename_0.PNG' | relative_url }}' alt='' title='' width='851' height='216' />

Your first project is now set up and ready to go.

| **ASIDE: Canadian census geography**“Census geography” refers to the geographic units used by Statistics Canada for disseminating information about the Census of Canada. Here are definitions of each of these types of units.* Province/Territory: “Portion of Canada’s land area governed by a political authority. Canada is divided into 10 provinces and 3 territories.” * Census Metro Areas (CMA): “Area consisting of one of more neighbouring municipalities situated around a core. A census metropolitan area must have a total population of at least 100,000 of which 50,000 or more live in the core.” There are 33 CMAs in Canada as of the 2011 census. * Census Division (CD): “Group of neighbouring municipalities joined together for the purposes of regional planning and managing common services (such as police or ambulance services).” In Toronto, the amalgamated City of Toronto corresponds to the Census Division unit. * Census Subdivision (CSD): “Area that is a municipality or an area that is deemed to be equivalent to a municipality for statistical reporting purposes (e.g. as an Indian reserve or an unorganized territory). Municipal status is defined by laws in effect in each province and territory in Canada.” The Toronto CSD is the same as the CD (see above), because of amalgamation. * Census Tract (CT): “Area that is small and relatively stable. Census tracts usually have a population of 2,500 to 8,000 persons. They are located in large urban centres that must have an urban core population of 50,000 or more.” * Dissemination Area (DA): “Small area composed of one or more neighbouring dissemination blocks, with a population of 400 to 700 persons. All of Canada is divided into dissemination areas. It is the smallest standard geographic areas for which all census data are disseminated”. * Canada Postal Code: “The postal code is a six\-character code defined and maintained by Canada Post Corporation for the purpose of sorting and delivering mail.”  Source: [Statistics Canada’s census dictionary](https://www12-statcan-gc-ca.myaccess.library.utoronto.ca/census-recensement/2011/ref/dict/azindex-eng.cfm). |
| --- |

 

[STEP 3: **Creating a Thematic Map**](#Step3)

This step will bring you through a number of the functions available on SimplyAnlaytics, with the ultimate goal of*making a map of average houshold income by sensus subdivisions within the Toronto CMA*. Our work will be broken up according to the development of the following skills:

a) Navigating and Exploring the Map

b) Selecting a Variable

c) Refining the Location

d) Legend Editor

e) Map Management

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

**A) Navigating and Exploring the Map**

Use the map toolbar to navigate and explore the map you have created.

<img src='{{ '/assets/images/098-CLAREExploring.png' | relative_url }}' alt='' title='' width='721' height='451' />

Click the “**i**” icon to activate “information” mode. **Click on any census subdivision** on the map. The information window will appear, telling you the name of the census subdivision as well as the total population for that location (or whatever other information you are mapping: population is generally the default having made a new project). Notice you can also add any individual location showing on a map to a new project, or to your favourites list. You could also give this location a custom name if you wished, using the “Add alias location name” option. When you have finished looking at the details, **close the information window**.

<img src='{{ '/assets/images/099-EXTRAinfoicon_0.png' | relative_url }}' alt='' title='' width='648' height='526' />

**B) Selecting a Variable**

Notice the panel at the left side of the screen. It has three tabs, “Locations”, “Data” and “Businesses”. Select the **Data** tab if it is not already selected.

The individual data characteristics that you can include on your map are known as “variables”. Various categories of variables are listed in the Data tab. Click on **Income**. The variable selection panel appears.

<img src='{{ '/assets/images/SImplyAnalytics_01.png' | relative_url }}' alt='A list of data characteristics that can be included on your map.' title='' width='600' height='328' />

At the right\-hand side of the panel is a list of possible variables to add to the map. There are quite a lot of them! There are variables that show the total number of individuals or households making a certain income range, as well as variables showing total, average, or median income. You can use the various filter options to narrow down your options if you like. For example, under “Data Type”, select **average**. The selection you have made appears at the top of the window as a blue box, which can be removed at any time if you change your mind.

<img src='{{ '/assets/images/012-var-selector2.PNG' | relative_url }}' alt='' title='' width='749' height='572' />

Let’s take a closer look at the third variable in the list, “Households by Income (Current Year) \| Average Household Income (Current Year $)”. You can find out more about this variable by clicking the menu button (vertical ellipsis) and choosing **View Metadata**.

<img src='{{ '/assets/images/012-var-selector3.png' | relative_url }}' alt='' title='' width='749' height='572' />

The “Variable Metadata” window appears. Here you can find out some additional details about this variable. We can see that it is an estimate variable for the current year (2017\) and that it comes from an organization called Environics. So, we have determined that this data is not official census data from Statistics Canada. That doesn’t mean it is bad, it is simply important to be aware of your data sources, and to cite them correctly when you use them in your academic work.

<img src='{{ '/assets/images/014-view-metadata.PNG' | relative_url }}' alt='' title='' width='664' height='479' />

Close the metadata window when you have finished reviewing the information.

Click on the vertical ellipsis for our variable of interest again and select Use this Data Variable. Notice that the variable now has a check mark on it. You can add as many variables as you like at once, and later you will be able to toggle which one is shown on the map. For now we will just add the average income variable.

<img src='{{ '/assets/images/016-var-selector5.PNG' | relative_url }}' alt='' title='' width='620' height='602' /> <img src='{{ '/assets/images/017-var-selector6.PNG' | relative_url }}' alt='' title='' width='592' height='601' />

One final thing before we close this window.  Click on the menu button for our variable of interest again and select **Add to Favorites**.

<img src='{{ '/assets/images/015-var-selector4.PNG' | relative_url }}' alt='' title='' width='732' height='695' />

You can add any variable to your favourites list in order to find it again easily in the future. Keep in mind however that if you signed in as guest, the selection will not actually be saved for next time.

Now close the variable selection panel. In the data panel, you can click on the star icon and all the variables you have favourited will be available.

<img src='{{ '/assets/images/018-favorites.PNG' | relative_url }}' alt='' title='' width='303' height='462' />

Now have a look at your map. Notice that the variable being displayed is now the household income variable. Click on the drop\-down menu. At any time, you can choose amongst all the variables that have been added to this map. Right now, we have the three default variables SimplyAnalytics always adds, plus our household income variable. Leave the income variable selected.

<img src='{{ '/assets/images/019-variables.PNG' | relative_url }}' alt='' title='' width='782' height='427' />

**C) Refining the Location**

We’ve already chosen to create our map of the Toronto CMA. However, right now the map is showing CMA broken down by Census Divisions. We want to show Census Subdivisions. Click on the drop\-down menu for Census Divisions, and change the selection to **Census Subdivisions** instead.

<img src='{{ '/assets/images/020-change-geo-breakdown.PNG' | relative_url }}' alt='' title='' width='702' height='292' />

The map will refresh and now the light grey boundaries will show smaller regions which correspond to municipalities. Some select municipalities will be labelled.

Note also that you can change your overall geography at any time by selecting the **Locations** tab in the left\-hand panel. You can search for a new location there. For example, search for **Hamilton**. Click the **CMA option** for Hamilton.

<img src='{{ '/assets/images/021-change-geo-map.PNG' | relative_url }}' alt='' title='' width='304' height='279' />

Your map will now show Hamilton instead.  Now, in the drop\-down menu above the map, you can choose between the Toronto and Hamilton CMAs at any time.

<img src='{{ '/assets/images/022-change-geo-map2.PNG' | relative_url }}' alt='' title='' width='537' height='323' />

You also have several options for creating custom locations. Let’s imagine that your research area actually includes both the Toronto and Hamilton CMAs and you want to map them both at the same time. On the Locations tab, click **Custom Locations**, then**Create new combination location**.

<img src='{{ '/assets/images/023-combination-location.PNG' | relative_url }}' alt='' title='' width='301' height='422' />

The “Create Combination Location” window appears. In step 1, give your custom combination location a **name**. In step 2, search for Toronto and Hamilton and **add each CMA to the list**. When your settings match the screenshot below, click **Save**.

<img src='{{ '/assets/images/024-combination-location2.PNG' | relative_url }}' alt='' title='' width='811' height='602' />

The combination location will appear on the map, outlined in yellow. In the drop\-down menu at the top of the screen, this location will now also be available.

<img src='{{ '/assets/images/025-combination-location3.PNG' | relative_url }}' alt='' title='' width='561' height='631' />

Another custom location option is to create a radius location. This can be used to create a radius of a specified distance around a location. This is often used for small geographies. For example, imagine you wanted to study the neighbourhoods near the University of Toronto campus. You could create a radius location of 2km from the centre of campus to delineate your study area. Let’s create this now. In the Location tab, select **Create new radius location**.

<img src='{{ '/assets/images/026-radius-location.PNG' | relative_url }}' alt='' title='' width='305' height='393' />

The ”Create Radius Location” window appears. Let’s try to pinpoint the centre of campus as closely as we can by searching for the postal code of the downtown campus, **M5S 1A5**. Notice that the search results suggest a dissemination area, DA4157\. Dissemination area is the most detailed census geography that we can map data for. You can search for postal codes in SimplyAnalytics, and the system will map them to the dissemination area in which they fall. This is handy because, while postal codes are often familiar to us, we rarely know dissemination area codes off the top of our heads! Click on the suggested dissemination area to select it.

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

Let’s go back to the Toronto CMA to continue designing our map. Choose Toronto from the drop\-down menu at the top of your map. Make sure Census Subdivisions is still selected as the geographic breakdown.

**D) Legend Editor**

This map isn’t really very interesting. Almost the entire CMA is displayed as one colour! You can make some changes in the legend to display the data more clearly. On the legend in the top right\-hand corner of the map, click **Edit**.

<img src='{{ '/assets/images/031-legend.PNG' | relative_url }}' alt='' title='' width='250' height='443' />

The Legend switches to edit mode. Change the classification method to **Quantiles (Local)**. Notice how the income ranges get adjusted and the map now depicts the differences between the CSDs more clearly. You can also explore the other classification methods if you desire.

<img src='{{ '/assets/images/032-legend-classification.PNG' | relative_url }}' alt='' title='' width='254' height='239' />

If you like, you can change your map’s colour scheme. If you’re finding it difficult to see the grey outlines of the Census Subdivisions, you could make their outlines thicker (e.g. change the thickness to 2\). You could change the outline colour if you like as well.

<img src='{{ '/assets/images/033-legend-colour-scheme.PNG' | relative_url }}' alt='' title='' width='249' height='416' /><img src='{{ '/assets/images/034-legend-outline.PNG' | relative_url }}' alt='' title='' width='277' height='416' />

When you’re finished editing the legend, click **Done**. Your map may look something like the screenshot below.

<img src='{{ '/assets/images/034_2-edited_map.PNG' | relative_url }}' alt='' title='' width='864' height='641' />

**E) Map Management**

There is no need to save the maps you create in SimplyAnalytics – they are saved automatically and appear within your project as “views” listed down the right\-hand side of the screen. We have been working on the listing currently called “Map”. (We’ll be looking at the comparison reports and rankings a bit later). Click on the **tiny arrow** at the top left\-hand corner of the Map listing, and select **Rename**.

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

[**EXERCISE 1**](#Ex1)

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

[STEP 4: **Mapping Business Locations**](#Step4)

You may have noticed a tab in the side panel called Businesses, which we haven’t worked with yet. This allows you to add business locations and points of interest to a map or report. Let’s do so now, with our **Toronto Avg Income** map. Click on the map in the views listing to activate it.

Select the Businesses tab in the left\-hand panel. You can search for points by typing a keyword, business name, NAICS code or SIC code into the search box.

For example, imagine you wished to show all the Canadian Tire stores in the Toronto area on the map. Enter **Canadian Tire** in the search box and hit **Enter**.

<img src='{{ '/assets/images/048-business-search.PNG' | relative_url }}' alt='' title='' width='1043' height='540' />

The matching businesses are immediately shown on the map, and the search phrase is included in the legend.

**Note:** when you see numbers written on the dots, that means there is actually more than one matching point located in that area. When you are zoomed out to the entire GTA, the locations can’t all be shown at once, and instead they are generalized and grouped. If you zoom in you will start to see individual points. Go ahead and zoom in.

<img src='{{ '/assets/images/049-business-map.PNG' | relative_url }}' alt='' title='' width='709' height='525' />

You can search by category of store as well as by specific store name. In the search box, type **hardware store** and hit **Enter**. Your new search replaces your old search on the map and in the legend.

<img src='{{ '/assets/images/050-business-map2.PNG' | relative_url }}' alt='' title='' width='744' height='591' />

Another option is to browse businesses by category. Instead of typing in a search term, click **Browse business categories**. This allows you to browse categories according to NAICS (North American Industrial Classification System) codes. Click **44 Retail Trade**, then **4441 Building Materials and Supplies Dealers**, then **444130 Hardware Stores**. The map updates.

<img src='{{ '/assets/images/051-browse-naics.PNG' | relative_url }}' alt='' title='' width='987' height='306' />

**Click on any hardware store point** on the map. An information window appears. This window shows all the information available about this particular business. It’s address, several business classification systems (including NAICS as well as SIC or Standard Industrial Classification system), its sales volume and the number of employees at that location. Notice that in this case the NAICS code is not actually listed as 444130 which we searched for. This is because each business has a “primary NAICS” and up to 6 additional relevant NAICS codes assigned. Businesses will be shown on the map if any of the assigned NAICS codes match our search, but only the primary NAICS code is displayed in the information window. There are other ways to view all assigned NAICS codes, which we’ll see later.  Close the information window.

<img src='{{ '/assets/images/052-business-info.PNG' | relative_url }}' alt='' title='' width='438' height='459' />

The final, and most sophisticated, way to identify businesses is to use advanced search. Click on **Use advanced search** in the Businesses panel. The “Advanced Business Search” window appears. Let’s first add a search parameter to find the NAICS code for hardware stores, similar to what we did previously. In the first box choose **NAICS**. In the second box, select **Starts with**. When you click in the third box, a browse menu comes up. Drill down until you get to **444130 \- Hardware Stores**.

<img src='{{ '/assets/images/053-business-advanced.PNG' | relative_url }}' alt='' title='' width='704' height='501' />

Next click **Add condition**.

<img src='{{ '/assets/images/054-business-advanced2.PNG' | relative_url }}' alt='' title='' width='501' height='425' />

For this condition, in the first box, choose **Sales Volume**. In the second box choose **Is greater than**. In the third box, type **5000000** (five million). We’ll find hardware stores with a sales volume greater than $5million annually. Click **Search**.

<img src='{{ '/assets/images/055-business-advanced3.PNG' | relative_url }}' alt='' title='' width='498' height='421' />

Again, the map and legend update with the results of our search.

If you like, you can edit the name of your point set within the legend by clicking on it. For example, change the name to **Hardware stores, sales vol\>$5M** (the number of characters is limited).

<img src='{{ '/assets/images/056-business-rename-legend.PNG' | relative_url }}' alt='' title='' width='527' height='278' />

 

[**EXERCISE 2**](#Ex2)

Switch to your Exercises map.

***Task: Add a set of businesses to the map you created in Exercise 1\. Choose a zoom level that you think works well for your data, and give your business set a name in the legend.***

Take the time to play around with the different search options for refining your set of businesses.

 

[STEP 5: **Options** for **Exporting**Maps](#Step5)

Choose the Toronto Avg Income map. If necessary, zoom out so that the entire Toronto CMA (yellow outline) is showing. Click the **View Actions** button near the top right\-hand corner of the screen. Here is where you can set some additional view options before you export a map:

* **Show Legend:** toggle the legend on and off.
* **Show Map Labels:** label the geographic locations on the map.
* **Highlight Location:** toggle the yellow border on and off.
* **Apply Location Mask:** only show data within the yellow border

The **Export Shapefiles** option is a very useful option as well, it allows you to download the thematic map variable as a shapefile (geospatial data file) for use in Geographic Information Systems (GIS).  
<img src='{{ '/assets/images/057-view-actions.PNG' | relative_url }}' alt='' title='' width='326' height='424' />

\*Note: the business locations cannot be directly downloaded as a shapefile.\*

If you do not want a shapefile, you will instead  click on the **Export** button once you have finished setting your view options.

<img src='{{ '/assets/images/058-export.PNG' | relative_url }}' alt='' title='' width='308' height='57' />

The “Export Map” window appears. This is a 3\-step process. In Step 1, **drag the dotted outline** until the map area you wish to export is all included. Select different paper size and orientation if desired. When you are finished, click **Continue to Layout**.

<img src='{{ '/assets/images/059-export2.PNG' | relative_url }}' alt='' title='' width='1200' height='699' />

In Step 2, make any layout adjustments you desire. For example, change the Legend Theme to **Dark**. Add an inset map and a north arrow. Drag these items around the map until they are in your desired location. When you are finished, click **Continue to Export**.

<img src='{{ '/assets/images/060-export3.PNG' | relative_url }}' alt='' title='' width='1194' height='779' />

In Step 3, select your desired file format (e.g. **PDF**). Change the toggle option from Email to **Save to computer**. Click **Finished**.

<img src='{{ '/assets/images/061-export4.PNG' | relative_url }}' alt='' title='' width='401' height='309' />

When your download is finished, you can open it and check how it turned out.

<img src='{{ '/assets/images/062-exported.PNG' | relative_url }}' alt='' title='' width='1200' height='740' />

[STEP 6: Creating **Reports**](#Step6)

This step will be broken up into three sections, along with two Exercises:

a) Creating a Business Report

EXERCISE 3

b) Creating a Comparative Report

c) Creating a Ranking Report

EXERCISE 4

\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-

**A) Creating a Business Report**

A businesses report view was already created when we started adding businesses to our map. Click on it now from the views bar.

The businesses report will appear. Along the top of the report, you can choose the businesses search you wish to display in your report. If your “Hardware stores, sales volume \>$5m” search is not selected, choose it now. The location should be set to Toronto CMA, though this can be changed as well from the drop\-down menu.

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

Your business report appears. You can continue to modify the report at any time by running new searches for businesses or places in the side panel. These will immediately become available in the drop\-down menus at the top of your report.

 

[**EXERCISE 3**](#Ex3)

***Task: Using the Businesses 2 report view, generate a businesses report. Give the report a new name, and export it to a file.***

Take the time to play around with the different columns available. Open up your exported file and have a look at it.

 

**B) Creating a Comparison Report**

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

Close the search window by clicking on the **X** in the top right\-hand corner. Our new variable has now been added to the “Edit Comparison Report” window. **Un\-select all other variables**, leaving only the mandarin speakers variable selected. Click **Done**.

<img src='{{ '/assets/images/077-comparison-report4.PNG' | relative_url }}' alt='' title='' width='661' height='574' />

You don’t necessarily have to be in “Edit Comparison Report” mode to add variables to the report. Let’s add the percentage of Cantonese speakers to the report as well. On the **Data** tab in the side panel, search for **cantonese** and add the % Household Population by Mother Tongue variable (by selecting **Use this data variable** from the options). Close the search results window. This variable is now included in the report.

<img src='{{ '/assets/images/078-comparison-report5.PNG' | relative_url }}' alt='' title='' width='524' height='319' />

At any time, you can remove a variable from the report by clicking on it, and choosing **Remove from this Report** from the pop up menu.

<img src='{{ '/assets/images/SimplyAnalytics_081.png' | relative_url }}' alt='More options for selected dataset in report' title='' width='573' height='520' />

When you click on a location, a pop up menu also appears, which will let you hide the location and will also give you some sorting options. Click on **Hamilton**, then choose **Sort, smallest to largest**.

<img src='{{ '/assets/images/080-comparison-report7.PNG' | relative_url }}' alt='' title='' width='526' height='418' />

The order the data variables are listed will change so that the one with the smallest value in Hamilton will be listed first.

Finally, just like with the previous report, you can rename it and export it if you desire.

 

**C) Creating a Ranking Report**

The ranking report will let you create a table view and compare data for all geographic units within a location, ranking them by your chosen variable. Every new project has one ranking report view included by default. Click **Ranking** on the views bar. (Note: you can always create more ranking reports by clicking New View). The basic ranking report appears.

<img src='{{ '/assets/images/081-ranking-report.PNG' | relative_url }}' alt='' title='' width='107' height='497' /> <img src='{{ '/assets/images/082-ranking-report2.PNG' | relative_url }}' alt='' title='' width='959' height='498' />

This report is displaying the census divisions within the Toronto CMA. It is displaying three variables by default, and sorting the table based on one of these variables (total population). Your default view may differ from the screenshot depending on what locations and variables you have used in your map.

***Task: Create a report to compare the expenditures on food and women’s clothing for all census subdivisions (municipalities) in both the Toronto and Hamilton CMAs.***

We can set up some of these parameters immediately using the drop\-down menus at the top of the screen. Change census divisions to census subdivisions. Change Toronto to the combination location we created earlier for Toronto \& Hamilton CMAs. (As with all reports, you could search for new locations and create new custom locations using the Locations tab in the side panel at any time, and these would be added to your options list.)

<img src='{{ '/assets/images/083-ranking-report3.PNG' | relative_url }}' alt='' title='' width='671' height='258' />

Now we need to add our variables. In the **Data** tab on the side panel, choose the **Consumer Behaviour** category. In the search box, scroll down in the central panel until you find the date limit options. The default option is always going to be to give you the latest available data. In this case, the latest available is 2017\. Because the year 2017 is not yet over, we know that these data must be projections. If we want to use the most recent year for which complete data is available, we can select **2016**.

<img src='{{ '/assets/images/084a-browse-filter.PNG' | relative_url }}' alt='' title='' width='351' height='586' />

Now, to select the variable, let’s use the filter option. Type **food** in the filter box. Add the **Average Total Expenditure \| Food** variable to the table.

<img src='{{ '/assets/images/084-browse-filter.PNG' | relative_url }}' alt='' title='' width='1044' height='770' />

Next, change the filter term to **clothing**. Add the variable **Average Total expenditure \| Clothing \| Women’s and girls’ clothing (4 years and over) \| Women (aged 15 and over): Clothing** to the map.

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

Let’s make one further change. Let’s only show the census subdivisions (municipalities) where the expenditure on food is more than $12,000 on average annually. Click the **Filtering** button.  In step 1, click on the **average expenditure for food variable**. This variable will now appear in step 2\.  Add the expression **is greater than $12,000**.  Select **Hide** instead of Strikeout. Click **Apply**, then close the filtering window.

<img src='{{ '/assets/images/092-filtering.PNG' | relative_url }}' alt='' title='' width='926' height='731' />

Now only census subdivisions with average spending on food of more than $12,000 are displayed. Notice that the word “on” appears on the Filtering button to remind you of the filter you have set. You can remove the filter at any time by clicking on Filtering again and changing the filter toggle from On to Off.

<img src='{{ '/assets/images/093-filtering2.PNG' | relative_url }}' alt='' title='' width='348' height='242' />

Finally, just like with the previous report, you can rename it and export it if you desire.

 

 

[**EXERCISE 4**](#Ex4)

***Task: Explore the different reports. You can make any of the report types covered in this workshop, or go to New View and explore additional report options available in SimplyAnalytics.***

[STEP 7: **Getting** Help](#Step7)

The **Help Centre** has various articles describing how to accomplish different tasks in SimplyAnalytics.

<img src='{{ '/assets/images/095-support2.PNG' | relative_url }}' alt='' title='' width='769' height='495' />

If you still have questions, you can contact either the Map \& Data Library ([mdl@library.utoronto.ca](mailto:mdl@library.utoronto.ca)) or SimplyAnalytics support directly, through the links provided in the Support menu and Help Center.

Please also feel free to consult these official guides from SimplyAnalytics:

* [SimplyAnalytics Canada FAQ](https://mdl.library.utoronto.ca/sites/default/public/mdldata/open/international/simplyanalytics_guides/Canada%20FAQ_Standard.pdf)
* [SimplyAnalytics Canada FAQ \- PRIZM database](https://mdl.library.utoronto.ca/sites/default/public/mdldata/open/international/simplyanalytics_guides/Canada FAQ Sheet_PRIZM_PremD&B.pdf)
* [SimplyAnalytics USA Exercise Guide](https://mdl.library.utoronto.ca/sites/default/public/mdldata/open/international/simplyanalytics_guides/SimplyAnalytics USA Exercise Guide - Answering Research Questions - Standard.pdf)

Technique: [Data Visualization](/technique/data-visualization), [Searching for maps and data](/technique/searching-maps-and-data) \| Tools: [SimplyAnalytics](/tools/simplyanalytics-0) \| Data Format: [Statistics](/data-format/statistics), [Vector](/data-format/vector)**Date Created:** 2018\-01\-04**Updated:** 2025\-01\-27
