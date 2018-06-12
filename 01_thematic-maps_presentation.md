---
title: "Thematic Maps in Social Explorer: Presentation"
author: Francesca Giannetti, Digital Humanities Librarian, Alexander Library
date: May 18, 2018
mainfont: EB Garamond
fontsize: 11pt
thanks: This presentation is an adaptation of Janine Billadello's "Introduction to Social Explorer" (2015), <http://faculty.baruch.cuny.edu/geoportal/resources/census/social_explorer.pdf>.
abstract: This presentation will introduce you to Social Explorer, an online mapping tool that allows you to explore and visualize demographic data. We will explore the tool's basic capabilities, and make sample maps using data from the American Community Survey (ACS). This presentation will show you how to generate, edit, and export a completed, customizable map. Instructions for how to download summary spreadsheet data from the ACS and Decennial Census are also provided. Brief explanations of these datasets are given at the end of this document.
---

<!-- pandoc -s -f markdown+smart -V geometry:margin=1in -V urlcolor:Maroon fernandez_presentation.md -o fernandez_presentation.pdf -->

## Getting Started

The Rutgers University Libraries subscribe to the Professional Edition of Social Explorer. If you are using a computer on campus, the Professional Edition will launch automatically when you go to the website
<http://www.socialexplorer.com>. If you are off-campus, you need to access
Social Explorer via the RUL website in order to use the Professional Edition. The RUL link to Social Explorer is <https://www.libraries.rutgers.edu/indexes/socialexplorer>. 

1. From the Social Explorer homepage (Fig 1), clicking the Start Now button will take you directly to the mapping interface. You should find yourself looking at a map of North America, with the United States highlighted. By default the map displays Population Density (per sq. mile) by State based on the latest estimates from the 5-year American Community Survey (ACS). The colors are graduated so that lighter areas represent lower population density, while darker areas have higher population density.

![Social Explorer homepage][1]

[1]: imgs/homepage.png

2. Using the search bar in the upper left-hand corner of the map, type "169 College Ave, New Brunswick, NJ 08901" (the address for Alexander Library), press enter, and the map will zoom to that location, as well as mark it on
the map. Note that the map is now divided into smaller units called census tracts. If you hover the cursor over a census tract on the map, you will get a pop-up window with the name of the tract, as well as the population density estimate for that tract. The color bar at the top of the screen shows which colors correspond to which population densities.

## Navigation

1. Practice moving around by left-clicking and dragging the mouse to pan across the map. Use the mouse wheel to zoom in and out, or click the +/- buttons in the lower left-hand corner of the map. Notice how the map auto-regenerates as you move or alter the scale.

2. Social Explorer offers multiple ways to spatialize and visualize data. Under the map title, you will see a tab labeled Show data by, clicking this will open a drop-down menu of options. In order to activate these options, you must click the switch next to Automatic from On to Off. Click the radio button next to Census Block Group and see what happens to the map (Fig 2).

![Census Block Groups][2]

[2]: imgs/college-ave.png

For this exercise, we will concentrate on Census Tracts and Block Groups, which are defined as: 

**Census Tract**: a statistical area designed to have an optimal size of 4,000 residents, with a general range of 1,200 to 8,000. Tracts never cross county boundaries. Available in the decennial census and ACS 5-year
estimates.

**Block Groups**: statistical divisions of census tracts, are generally defined to contain between 600 and 3,000 people.  A block group consists of clusters of blocks within the same census tract.

As a general note, here are the principal census geographies, in descending order of size, and their quantity for the state of New Jersey. Think of them as a Russian matryoshka doll.

New Jersey (2010)

-  21 **counties**
-  2,010 **census tracts**
-  6320 **block groups**
-  169,588 **census blocks**  

## Make a Map

1. Let's visualize data other than Population Density. The Change Data button in the upper left-hand corner of the screen allows you to explore the available data. Click the Browse by Category tab, and you will see numerous pre-categorized options based on the ACS 2016 (5-year) estimates. As an example, let's say we wanted to look at the Hispanic or Latino population in Central New Jersey. You can get to it in a few ways from the Browse by Category tab (Fig 3), either by selecting Race, or, Asian and Hispanic Groups. Check the box next to **Hispanic or Latino by Specific Origin > Hispanic or Latino**. The map should generate automatically upon clicking the variable within the list.

2. In the Show data by dropdown menu, change the geography to Census Tract, if it is not already set to this geography.

![Browse by Category][3]

[3]: imgs/browse-by-category.png

3. You should now have in front of you a map color-coded by the quantity of households people of Hispanic or Latino descent. Mouse over the census tracts to see the estimated number of Households in a given tract, and the estimated number and percentage of those households. To access more detailed information about the data displayed, click on the information ("i") button on the right of the Change Data button to access the Data Dictionary (Fig 4). The Data Dictionary will give you full narrative definitions of the categories as defined by the U.S. Census.

![Data Dictionary][4]

[4]: imgs/data-dictionary.png

4. Social Explorer uses various default settings for colors, geographies, data layers, visualization type, and the classification of numeric data. You don't have to accept them. You can change the color ramp by clicking the dropdown arrow next to the color-coded key in the upper right-hand corner (Fig 5). We're interpreting population as a continuous variable, so let's select from among the sequential or graduated (goes from lightest to darkest) color ramps. 

![Color][5]

[5]: imgs/color.png

5. You can change the classification of your data by clicking the dropdown arrow next to the color-coded key and selecting the Cutpoints menu. Social Explorer defaults to 11 classes using Category classification. Depending on the data you have selected, you may want to alter these defaults. For instance, to show a more highly contrasted (less graduated) map, lower the number of classes. You may wish to manually edit the cutpoints of the classes, or use one of the standard classification methods provided by Social Explorer. Click on the dropdown menu under Classification method and change it to Natural breaks (Jenks). Natural breaks classification will minimize the variation within classes and maximize the differences between classes. The features are divided into classes whose boundaries are set where there are relatively big differences in the data values.[^fn1]

6. The Hispanic population is displayed using a shaded area visualization with a graduated color scheme, but this is not the only possible visualization type. Social Explorer offers three ways to visualize your data: Shaded area, Bubbles, and Dot Density. Some of the data categories will not show all three of these options because of the nature of the data. Our population data will work with all three, since it is based on an estimated count of households. Click the Visualization Type menu at the top of the screen, and select Dot Density (Fig 6). 

![Dot Density][6]

[6]: imgs/dot-density.png

For each census tract, dots representing a quantity (in this case 10, that is 10 households) are distributed throughout the census tract, thus you are now viewing clusters where the Hispanic population is highest by count.

7. The Dot density visualization is probably best adapted to showing two or more categories of data. Click on the Change Data menu, uncheck the box next to **Total Population > Hispanic or Latino**, and instead check the boxes next to two or more national origins. For instance, Mexican and the Dominican Republic.

8. Go to the Menu button (three horizontal dashes in the upper right corner), and click Annotate Map (Fig 7). Click the Marker button, and click on Census Tract 51 to place a marker there. In the box under Marker Title, type "Rutgers University" and then change the Show title on map switch to On. Change the Text color to black. 

9. Click the button under Marker Icon to change the appearance of the icon. Since Rutgers is a university, let's select the college marker to change the icon to a graduation cap, and change its color to black.

![Annotations][7]

[7]: imgs/annotations.png

Click Back, and then Click Done to finalize your changes.

## Double Layout Maps

Social Explorer allows you to compare variables by visualizing them either as a Side by side or Swipe map. You can compare two different variables, or compare the same variable across different time periods. We're going to visualize per capita income for greater New Brunswick for the population as a whole and for the Hispanic population.

1. Click the black circular (double-layout) button in the lower center of the screen and select Side by side to generate a second copy of the map screen, which should replicate your Mexican and Dominican population data.

2. Let's change our data. On the right side, click on **Change Data > Browse by Survey > ACS 2016 (5-Year Estimates)** (Fig 8). Select dataset: Social Explorer Tables: ACS 2016 (5-Year Estimates). Select Table 91 (T91) Per Capita Income (In 2016 Inflation Adjusted Dollars)(Hispanic or Latino). Check the box next to variable: Per Capita Income. The visualization type should change back to shaded area. Make sure that the data are shown by the Census Tract geography. 

![Select by Survey][8]

[8]: imgs/select-by-survey.png

3. Now let's change the data on the left side. Go through the same data selection process as above, but select T83-Per Capita Income (In 2016 Inflation Adjusted Dollars). 

*Note*: If you mouse over a census tract, the information box will now display information from both variables shown in your maps, regardless of which side you are on.

4. Zoom both maps out to the same scale (try 1 mile, shown on the scale bar at the bottom left of the screens), and position the Rutgers annotation in the center of each window (Fig 9).

5. The map titles can be edited by clicking the Edit button next to the existing title (which by default displays the survey and variable names). Change the title on the map on the left to "Per Capita Income (Whole Population)" and the on on the right to "Per Capita Income (Hispanic Population)" leave the source designations as they are.

![Side by Side][9]

[9]: imgs/side-by-side.png

Click Save to save your edits.

## Save and Share Your Work

In addition to the institutional login, Social Explorer also supports personal logins, and I recommend creating one to save your work. You may authenticate through your Google account (Gmail or Scarletmail). You can then access all your saved maps by navigating to the Social Explorer home page and clicking on My Projects. Don't forget to save your changes as you work.

1. When you are satisfied with your completed map, Social Explorer allows you to export it as an image. It will export whatever your current view shows, so position your map window accordingly.

2. Click the Export button on the upper right portion of the screen, and you will be given the option to export your map as an Image (.png). You can size the image according to your preference; there are various default sizes under the dropdown menu next to Aspect ratio. When everything looks good, click EXPORT to download the image to your computer. 

## Create a Report

While Social Explorer is primarily a map-making tool, it can also be used to produce downloadable tables. You can access this feature without making a map.

1. If you wish to download a summary table of the variables listed under each category, click on the Social Explorer icon in the uppermost left-hand corner to return to the home page. Under American Community Surveys (5-Year Estimates), find the 2012-2016 estimates and select BEGIN REPORT.
 
2. We're going to make a report for Hispanic or Latino households by country of origin in Middlesex County. Under geographic type, select County, then State: New Jersey, and geographic area: Middlesex County, New Jersey. Click the Add button, then Proceed to Tables. Choose T15. Hispanic or Latino by Specific Origin. Click Add, then Show results. 

![Report][10]

[10]: imgs/report.png

You can download the data report in different formats (Fig 10). Click on the Excel tab of the Results page. Output percents should be selected by default, but if not, click the box next to it to select it. Then click on the Excel 2007 icon to download the data as an .xlsx file. Unfortunately, there are no filtering options, so you must download the entire report for a data category and then edit the Excel table if you wish to isolate certain variables.

## About the Data

- **Decennial Census** The decennial census is a 100% count of the population taken every ten years. The data represents a snapshot of the nation at a fixed point in time. The number of variables from the 2010 census forward is limited to basic demographic characteristics of the population: race, gender, age, households, family relations, housing units, housing occupancy, and tenure (owner versus renter occupied). The Decennial census from 2000 and back contains most of the data that is now part of the ACS. Decennial census data is available for practically all geographic areas. The most commonly used series in the dataset is Summary File 1 (SF1).  
<https://www.census.gov/programs-surveys/decennial-census/decade.2010.html>

- **American Community Survey (ACS)** The ACS is a sample survey of the population that is compiled every year. Since it's a survey (based on rolling monthly samples) and not a count, the values represent estimates with a 90% confidence interval and margins of error for 1-year, 3-year, and 5-year periods. The number of variables is more extensive than the decennial census; in addition to basic demographic characteristics the ACS also includes socio-economic data like citizenship, educational attainment, income, occupation, home value,
and much more. Geographically, the data is more limited; geographic areas with 65k residents or more are published annually, areas with 20k residents or more are published as 3-year averages, and areas with less than 20k residents down to census tracts are published as 5-year averages.  
<http://www.census.gov/acs/www/>

The U.S. Census did not ask a question about Hispanic origin until 1970, and by most accounts, the resulting count was unreliable because it simultaneously over- and under-counted the relevant population. The resulting count from the 1980 census was considered to be much more successful.[^fn2] 

[^fn1]: See <https://gisgeography.com/choropleth-maps-data-classification/> for an explanation of common data classification methods in GIS.

[^fn2]: See <http://www.pewsocialtrends.org/2010/03/03/census-history-counting-hispanics-2/> for more background.