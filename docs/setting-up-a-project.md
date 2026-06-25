---
title: "Setting up a Project"
parent: "Introduction to SimplyAnalytics"
layout: "home"
created_date: 2018-01-04
maintainer:
    - name: Leanne Trimble
      link: https://library.utoronto.ca/staff/leanne-trimble
nav_order: 2
---
## Setting up a Project
{: #setting-up-a-project}

In the “New Project” window, you first need to select a county. SimplyAnalytics contains data for Canada and the US, but you can only create a project for one country at a time. For your first project choose **Canada**.

You then need to focus the map on a particular area within Canada. Don’t worry, this can be changed at any time. It will simply provide your map’s initial view area. Type **Toronto** in the search box.

<img src='{{ '/assets/images/005-new-project2.PNG' | relative_url }}' alt='' title='' width='473' height='496' />

Notice that SimplyAnalytics makes several suggestions for Toronto. This is because there are several different geographic units used in the Canadian census, that have the name Toronto – there is a Toronto Census Metropolitan Area, a Toronto Census Division and a Toronto Census Subdivision. Have a look at the information box below (marked **ASIDE**) for details of what each of these mean. For this exercise, choose the Census Metro Area (which is the largest “version” of Toronto, including the city and its surrounding municipalities).

<img src='{{ '/assets/images/006-new-project3_0.PNG' | relative_url }}' alt='' title='' width='499' height='515' />

The Toronto CMA appears in a blue bar below the location search box. You could add additional locations to your project if you chose, but for now, let’s just use the one. Click **Next**.

A pop-up window appears letting you know that SimplyAnalytics will include three basic census variables in your project by default. We will add additional variables in when Creating a Thematic Map; for now, select **Create project**.

<img src='{{ '/assets/images/007-basic-vars_0.PNG' | relative_url }}' alt='' title='' width='693' height='693' />

When you create a new project, the initial view is always a map, though you can also create a range of reports (which we will look at later). Notice in the toolbar at the top of the map, that by default the map is displaying the total population (most recent available year) in the Toronto CMA. The Toronto CMA is represented by the yellow outline on the map. Notice the third box in the toolbar that says “by Census Subdivision”. SimplyAnalytics will always show you your chosen map geography broken down by another, more granular level of geography. Census divisions are represented by the light grey lines on the map. All of the options in this toolbar can be adjusted, which we will do in the sections to come.

<img src='{{ '/assets/images/008-default-map.PNG' | relative_url }}' alt='' title='' width='966' height='589' />

Click on the name of your project at the top of the screen. Give your project a **new name** of your choice. Hit **Enter** to save the new name.

<img src='{{ '/assets/images/009-rename_0.PNG' | relative_url }}' alt='' title='' width='851' height='216' />

Your first project is now set up and ready to go.


**ASIDE: Canadian census geography**  
“Census geography” refers to the geographic units used by Statistics Canada for disseminating information about the Census of Canada. Here are definitions of each of these types of units.
* Province/Territory: “Portion of Canada’s land area governed by a political authority. Canada is divided into 10 provinces and 3 territories.” 
* Census Metro Areas (CMA): “Area consisting of one of more neighbouring municipalities situated around a core. A census metropolitan area must have a total population of at least 100,000 of which 50,000 or more live in the core.” There are 33 CMAs in Canada as of the 2011 census. 
* Census Division (CD): “Group of neighbouring municipalities joined together for the purposes of regional planning and managing common services (such as police or ambulance services).” In Toronto, the amalgamated City of Toronto corresponds to the Census Division unit. 
* Census Subdivision (CSD): “Area that is a municipality or an area that is deemed to be equivalent to a municipality for statistical reporting purposes (e.g. as an Indian reserve or an unorganized territory). Municipal status is defined by laws in effect in each province and territory in Canada.” The Toronto CSD is the same as the CD (see above), because of amalgamation. 
* Census Tract (CT): “Area that is small and relatively stable. Census tracts usually have a population of 2,500 to 8,000 persons. They are located in large urban centres that must have an urban core population of 50,000 or more.” 
* Dissemination Area (DA): “Small area composed of one or more neighbouring dissemination blocks, with a population of 400 to 700 persons. All of Canada is divided into dissemination areas. It is the smallest standard geographic areas for which all census data are disseminated”. 
* Canada Postal Code: “The postal code is a six-character code defined and maintained by Canada Post Corporation for the purpose of sorting and delivering mail.”  Source: [Statistics Canada’s census dictionary](https://www12.statcan.gc.ca/census-recensement/2011/ref/dict/azindex-eng.cfm). 

**Technique:** [Data Visualization](https://mdlutoronto.github.io/tutorials-search/?technique=Data+Visualization), [Searching for maps and data](https://mdlutoronto.github.io/tutorials-search/?technique=Searching+for+maps+and+data) \| **Tools:** [SimplyAnalytics](https://mdlutoronto.github.io/tutorials-search/?tool=SimplyAnalytics) \| **Data Format:** [Statistics](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Statistics), [Vector](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Vector)
