---
title: "Mapping Business Locations"
parent: "Introduction to SimplyAnalytics"
layout: "home"
created_date: 2018-01-04
maintainer:
    - name: Leanne Trimble
      link: https://library.utoronto.ca/staff/leanne-trimble
nav_order: 4
---
## Mapping Business Locations
{: #mapping-business-locations}

You may have noticed a tab in the side panel called Businesses, which we haven’t worked with yet. This allows you to add business locations and points of interest to a map or report. Let’s do so now, with our **Toronto Avg Income** map. Click on the map in the views listing to activate it.

Select the Businesses tab in the left-hand panel. You can search for points by typing a keyword, business name, NAICS code or SIC code into the search box.

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

The final, and most sophisticated, way to identify businesses is to use advanced search. Click on **Use advanced search** in the Businesses panel. The “Advanced Business Search” window appears. Let’s first add a search parameter to find the NAICS code for hardware stores, similar to what we did previously. In the first box choose **NAICS**. In the second box, select **Starts with**. When you click in the third box, a browse menu comes up. Drill down until you get to **444130 - Hardware Stores**.

<img src='{{ '/assets/images/053-business-advanced.PNG' | relative_url }}' alt='' title='' width='704' height='501' />

Next click **Add condition**.

<img src='{{ '/assets/images/054-business-advanced2.PNG' | relative_url }}' alt='' title='' width='501' height='425' />

For this condition, in the first box, choose **Sales Volume**. In the second box choose **Is greater than**. In the third box, type **5000000** (five million). We’ll find hardware stores with a sales volume greater than $5million annually. Click **Search**.

<img src='{{ '/assets/images/055-business-advanced3.PNG' | relative_url }}' alt='' title='' width='498' height='421' />

Again, the map and legend update with the results of our search.

If you like, you can edit the name of your point set within the legend by clicking on it. For example, change the name to **Hardware stores, sales vol>$5M** (the number of characters is limited).

<img src='{{ '/assets/images/056-business-rename-legend.PNG' | relative_url }}' alt='' title='' width='527' height='278' />

 

### EXERCISE 2
{: #exercise-2}

Switch to your Exercises map.

***Task: Add a set of businesses to the map you created in Exercise 1 from Creating a Thematic Map. Choose a zoom level that you think works well for your data, and give your business set a name in the legend.***

Take the time to play around with the different search options for refining your set of businesses.

**Technique:** [Data Visualization](https://mdlutoronto.github.io/tutorials-search/?technique=Data+Visualization), [Searching for maps and data](https://mdlutoronto.github.io/tutorials-search/?technique=Searching+for+maps+and+data) \| **Tools:** [SimplyAnalytics](https://mdlutoronto.github.io/tutorials-search/?tool=SimplyAnalytics) \| **Data Format:** [Statistics](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Statistics), [Vector](https://mdlutoronto.github.io/tutorials-search/?dataFormat=Vector)
