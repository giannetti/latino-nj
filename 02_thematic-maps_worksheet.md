---
title: "Thematic Maps in Social Explorer: Worksheet"
author: Francesca Giannetti, Digital Humanities Librarian, Alexander Library
date: May 18, 2018
mainfont: EB Garamond
fontsize: 11pt
abstract: This worksheet presents a series of questions about the Hispanic and Latino population that will familiarize you with selecting, manipulating and presenting demographic data in Social Explorer. At the end, you will develop a question of your own, and find the census tables with the information that will enable you to explore or answer that question.
---

<!-- pandoc -s -f markdown+smart -V geometry:margin=1in fernandez_thematic-maps.md -o fernandez_worksheet.pdf -->

## Questions

1. **Question**: Where do most Hispanic or Latino people reside in the U.S.?  
    **Data**: American Community Survey 2016 (5-Year Estimates)  
    **Analysis**: Aggregate data by state and create a shaded area map. Change cutpoints to show a total of five classes and use Natural breaks (Jenks) algorithm to classify the data.

2. **Question**: Where does New Jersey fall in terms of the number and percentages of Hispanic people residing in the U.S.?  
    **Data**: American Community Survey 2016 (5-Year Estimates)  
    **Analysis**: Use the Tables feature of Social Explorer to create a report showing the information from T15 Hispanic or Latino by Specific Origin. On the Data Download tab, select "Output percents". Download the data as a CSV file and open in Excel. Find the column header called "Total Population: Hispanic or Latino" and do a descending sort to find out where New Jersey ranks in terms of raw population numbers. Next, find the column header called "% Total Population: Hispanic or Latino" and do a descending sort again to find New Jersey. What's the difference between raw population and percent population?  

3. **Question**: How many people originating from Spanish-speaking Temporary Protected Status designated countries are in New Jersey?  
    **Data**: American Community Survey 2016 (5-Year Estimates)  
    **Analysis**: Use Table B03001–Hispanic or Latino Origin by Specific Origin of the American Community Survey Tables and check the boxes next to Salvadoran, Honduran, and Nicaraguan. Visualize data by Census Tract.  

4. **Question**: How many U.S.-born versus foreign-born Hispanics are there in New Jersey?  
    **Data**: American Community Survey 2016 (5-Year Estimates)  
    **Analysis**: Use Table B06004I–Place of Birth (Hispanic or Latino) in the United States of the American Community Survey Tables and visualize all categories by county.  

5. **Question**: How many people speak Spanish at home as compared to Portuguese in New Jersey?  
    **Data**: American Community Survey 2015 (5-Year Estimates)  
    **Analysis**: Use Table B16001–Language Spoken at Home by Ability to Speak English for the Population 5 Years and Over of the American Community Survey Tables and visualize Spanish and Portuguese speakers by census tract. Change the visualization from shaded area to dot density, and adjust each dot to represent 25 households (lowest value). 

<!--
click on down arrow to right of "Change Data" to save variable. 
Total > Speak Spanish
-->

6. **Question**: What changes can be observed over time when studying where Hispanics and Latinos have lived in New Jersey?  
    **Data**: 1970 and 2010 decennial censuses   
    **Analysis**: Aggregate data by census tracts and create shaded area maps for the 1970 and 2010 censuses. Hint: The 1970 census was the first in which a question was asked about Hispanic heritage, but it was phrased as "Spanish Origin or Descent". Use Social Explorer's side by side or swipe map features to show changes over time.  
<!--
1. Click on the Change Data button and select Census 1990. 
2. Under the Race category, check the box next to Total Population > Hispanic.
3. Zoom into Greater New York City either with the Zoom buttons or by using the search bar to search for New York, NY. 
4. Change the geography for data display to Census Tract, the smallest of the available options. 
5. At the bottom center of the screen, click the map view icon, and select Side by side. You should now have a split view showing the same data on the left and right sides. 
6. Let's change the data on the right side. Click on the Change Data button and select Census 2010. Repeat step #2 to select the Hispanic population.
7. Try alternating between the side-by-side and swipe map features. What changes do you observe? What are some plausible explanations for those changes?
-->

7. **Question**: What patterns can be observed in the levels of educational attainment of Hispanic men and women in New Jersey?  
    **Data**: American Community Survey 2016 (5-Year Estimates)  
    **Analysis**: Use Table C15002I–Sex by Educational Attainment for the Population 25 Years and Over (Hispanic or Latino) to create a shaded area map. Create a side-by-side map showing men with a bachelor's degree or higher on one side and women with the equivalent training on the other.  

## Over to you!

Develop a question of your own. See if Social Explorer provides access to the data you need to answer your question. Analyze it by by selecting a geography (e.g. state, county, census tract) and a type of map visualization (e.g. shaded area, dot density, bubble) that illustrates a clearly observable pattern.
