---
title: "Narrative Mapping: Presentation"
author: Francesca Giannetti, Digital Humanities Librarian, Alexander Library
date: June 5, 2018
mainfont: EB Garamond
fontsize: 11pt
---

<!-- pandoc -s -f markdown+smart -V geometry:margin=1in -V urlcolor:Maroon  fernandez_narrative-mapping-presentation.md -o fernandez_narrative-mapping-presentation.pdf -->

## Introduction

> ... \[H\]istorians exercise *selectivity*, *simultaneity*, and *shifting of scale* in manipulation of space and time to construct narratives that interpret the past. Selectivity is necessary so that historians can simplify a complex reality into something manageable for a study. When selected events expand over space and time, historians examine multiple places at once (i.e., simultaneity) and shift scales when they use a particular episode to make a general point. *Scale shifting* is a fundamental tool for narration in history, and *simultaneity* leads to the study of histories as mapping the past landscape. Landscape patterns of historical events constitute the structure that historians observe in the present.[^fn1]

A narrative map is an invitation to think about your topic from a variety of overlapping, non-exclusive perspectives. There is the Cartesian perspective of X and Y (longitude and latitude) coordinates on a two-dimensional plane, and there is the three-dimensional, lived world of landmarks, places and landscapes. Adding the fourth dimension of time, you can analyze the same place over different moments in history, or events happening in two different places at the same time. 

Narrative maps also support an array of storytelling techniques. One can use the inherent ability of digital maps to pan and zoom in order to tell a story in a combination of long shots and closeups (to make a filmmaking analogy). Text, while still critical, cedes ground to other storytelling devices. There is the potential, indeed the obligation, to support your story using visual and spatial (and aural) information. 

Lastly, while it is a feature of the web that is often taken for granted, hypertext allows you to construct alternate pathways through and away from the story, providing moments for your reader to drill down into the detail, skip around, or even take a temporary detour to investigate a particular source.

This tutorial will touch upon these different perspectives and narrative techniques using ESRI's Story Maps as the creation and presentation platform.

## Getting Started

1. Create a free ArcGIS public account at <https://storymaps.arcgis.com>. My recommendation is that you authenticate through your Google account (either Gmail or Scarletmail). ArcGIS may take you to www.arcgis.com after you authenticate; if so, navigate back to <https://storymaps.arcgis.com>. 

2. Click on My Stories in the navigation menu, and create a new story using the Map Journal app. This will launch the Map Journal Builder (Fig 1).

![Map Journal Builder][1]

[1]: imgs/map-journal-builder.png

For the the examples in this presentation, I will be using the materials in this Google Drive folder: <http://bit.ly/2J9GhgF>. You may want to create a similar folder for your own materials. 

3. Select your preferred layout and press START. My examples will show the default Side Panel layout, but the steps are the same for the Floating Panel layout. 

4. Give your Map Journal a title (this can be edited later). 

## Home Section

Next, ArcGIS will prompt you to select content for the Home Section, or, the landing page that readers will see when they first visit your narrative map. Consider the Home Section your story's introduction. 

The dialog first prompts you for the Main Stage Content, in other words, the content that will occupy most of the screen, to the right of the side panel. Note that you can choose between a map, image, video, or web page. 

1. Here, we'll create an overview map showing all the locations we've identified as important to our oral history. Download your locations spreadsheet as a comma separated values (CSV) file (in Google Drive, File > Download as > Comma-separated values). Back in the StoryMaps Main Stage dialog, use the map dropdown menu to select **Create a map**. Give your map a short descriptive title.

2. The map editor window will appear, showing ESRI's Topographic basemap. In order to add your locations to the basemap, go to Add > Add layer from file (Fig 2). Click Browse and select the CSV file you just downloaded from GDrive. As a side note, you can manually search and add locations as Map Notes using the search box in the upper right. It's additionally possible to draw lines and shapes using the Edit menu (Fig 3). I encouraged you to assemble a spreadsheet of locations, however, because I think this task helps to think holistically about the structure of your narrative, while also allowing you to store your data outside of ArcGIS. 

![Add Layer from File][2]

[2]: imgs/layer-from-file.png

![Optional - Map Notes][3]

[3]: imgs/map-notes.png

3. The map editor will next ask you to choose an attribute of your data to show ("name" is fine) and a drawing style. I suggest selecting single symbol style. If you create a classification scheme for your data (e.g. historical events, personal events), then the unique symbol might suit better. Clicking on OPTIONS allows you to change the icon, color, size, and transparency of your map markers. Go to Shapes > Basic and select the pin of your choice (Fig 4). Zoom out the map so that all your map markers are showing on the map (adjust the size of the markers, if necessary) and click SAVE and CLOSE. 

![Style][4]

[4]: imgs/style.png

4. Back in the Main Stage Content dialog, clicking NEXT will prompt you to enter and format the Side Panel content for the Home Section. Here, you can paste text into the editor from your section outline document. You
can also upload or embed graphics, images and videos in with the text. More on this later. Press SAVE. Your completed Home Section will now appear in your Map Journal

## Add Sections

1. Click on ADD SECTION in the lower part of your screen to start the first section of your narrative. We once again start with the Main Stage part of the screen. Make sure the "map default" is selected for location, content, and pop-up (Fig 5). Select NEXT to move on to the Side Panel. 

![Map Default][5]

[5]: imgs/map-default.png

2. Paste your text for Section 1 into the editor of the Side Panel Content. We'll also create a Story Action for a portion of our text. With your cursor, highlight "born in Corsica" and click the pin icon for "Locate an address or place". Use the search box to search for Corsica, France. Click APPLY, and then ADD, to add the marker to your map (Fig 6). Now, if you notice, when you navigate from the Home Section to Section 1, your Main Stage map does not change until the reader clicks on the hyperlinked text. The reader may then click on the BACK button to return to the map overview. 

![Story Action][6]

[6]: imgs/story-action.png

## Add/Edit Maps

1. You can create a custom configuration of the main map for each section of your narrative. For instance, rather than create a Story Action, you could simply zoom the map to Cataño, Puerto Rico, for instance, for the following section. Be sure to save the custom configuration of the map for each section. 

2. ArcGIS allows you to create new web maps as well as use maps that have been created and publicly shared by other users. Let's create a new map by searching ArcGIS Online for a public dataset. In the Map dropdown menu in the Main Stage Content dialog, select Create a map. Give this new map a descriptive name (e.g. PR Pop) The map editor will load. Go to Add > Search for layers. In the next dialog, select ArcGIS Online from the dropdown menu and search for `puerto_rico_population` by `hmhs_rwoolner`. Select it and click Add to Map. Click the back arrows to return to the Content tab of the map editor. With your cursor, hover over "puerto rico population" and click on the "Show table" icon. You will see that this dataset comes with several columns of historic population data. Since Tom Olivieri left Puerto Rico for the United States in the late '40s or early '50s, let's create a shaded area map showing data from the `pop_1940` column. Close out of the table and select Change style (shapes icon). Under the attribute dropdown menu, select `pop_1940`. This variable opens up additional visualization possibilities. Select "Counts and Amounts (Color)" under drawing style, and then click DONE in the Style dialog. If you zoom into Cataño and select that municipality, it should show what Olivieri described, namely that Cataño was sparsely populated relative to San Juan across the bay (Fig 7). Save your changes to this new map and click CLOSE. In the Main Stage dialog for this section of your narrative, make sure your new PR Pop map is selected. If you like, you can do a custom configuration next to Pop-up to show the information window for Cataño. Click SAVE. 

![Puerto Rico Population (1940)][7]

[7]: imgs/pr-pop.png

## Add Media

1. Return to the Side Panel dialog for this section entitled Cataño. Underneath our text, let's add an openly licensed photo showing an aerial view of Cataño. Click on the camera icon (Insert an image, video or webpage) and select Flickr as the source. Enter user name 'Juan Cristobal Zulueta' and click Load albums. Select his Puerto Rico album and scroll until you see Cataño. In the image caption, add a citation, e.g. below. Select the checkbox next to 'Include a maximize button...' and click APPLY and SAVE.

`Juan Cristobal Zulueta, "Cataño," 2014, <a href="https://www.flickr.com/photos/28312366@N08/15313419317/sizes/l">Flickr</a>.`

Alas, the public accounts of ArcGIS Story Maps appear to have *very* limited storage. You will most likely need to store your images in either Flickr or Google+, and then embed them into your Story Map. Pursue Flickr and Google+ in priority, as these will be the easiest solutions. It's also possible to host images on the Rutgers RCI and Eden web servers, but the process will be a bit more involved. 

## Add Media (Embeds)

1. We'll skip ahead in the story to Hoboken in order to demonstrate how Social Explorer maps can be embedded into Story Maps. In Social Explorer, create a shaded area map showing the Puerto Rican population in Hoboken using the 1980 census dataset. Then, going to the share icon, click on the Embed tab, and copy the HTML code. Back in Story Maps, navigate to the Main Stage dialog for the appropriate section, and instead of using a map for the content, select Web page. Paste the HTML code into the Embed window. Then, click Configure. The default Fill and Unload should work fine, but note the other options. Click Next. You should now see an interactive web map from Social Explorer in the Main Stage of your Story Map section. 

## Finishing Details

- We can use Story Actions to add a table of contents on our Home Section. Edit the Side Panel of the Home Section to include an ordered list of your Sections (Fig 8). Select the text you want to use as the link, and click on the Navigate button (an up-and-down icon) in Story Actions. Click APPLY and then SAVE.

![Table of Contents][8]

[8]: imgs/toc.png

- The Map Journal Builder gives some options in terms of layout, colors, and fonts. Go to Settings in the upper navigation menu to explore. 
- You can also change the default Topography basemap that appears in the overview map. In the map editor, click on the Basemap tab and select another option. 
- You can use the Organize button at the bottom of the Map Journal Builder to reorder and delete sections. 
- When you're ready to go public with your work, click on Share in the upper navigation menu, let ArcGIS check your Story Map for issues, and then click Public. ArcGIS gives you a shortlink to share your Story Map with your professor, your friends, your family, and your social media followers. 
- Don't forget to save your work inside every editor at every stage!!!


## Sidebar: Finding Audio/Visual Material for Reuse

For scholarly digital projects, you will want to prefer still images and audiovisual material that are licensed for reuse. That license tells us that we can reuse the content without having to ask permission of the creator. In some cases, with web content, you will not be able to identify a clear license. If you've already done your best to find openly licensed content and have come up empty-handed, you may make selective use of what will be presumed to be copyright-protected material by including as full a citation as possible and by directly commenting on, critiquing, or analyzing that material in the Side Panel.[^fn2]

**Places to look**: 

- **Google Advanced Image Search** <https://www.google.com/advanced_image_search>
    + You can make sure that the images you select from are licensed for reuse by scrolling down to the last field, usage rights, and selecting “free to use and share.” 
- **Flickr** <https://www.flickr.com/> 
    + Story Maps already has an integration with Flickr, making it very easy to embed images hosted on this platform. In fact, if you already have a Flickr account, it makes sense to host your Story Maps images here. After you launch a keyword search in Flickr, you can restrict your results by license (e.g. all creative commons, or no known copyright restrictions).
- **Creative Commons Search** <https://search.creativecommons.org/>
    + For easy searching of YouTube and/or SoundCloud for openly licensed audio/visual material, you may prefer Creative Commons Search. Uncheck the box next to "use for commercial purposes."


[^fn1]: Yuan, Mary, John McIntosh, and Grant Delozier. “GIS as a Narrative Generation Platform.” In *Deep Maps and Spatial Narratives*, edited by David J. Bodenhamer, John Corrigan, and Trevor M. Harris, 179–202. Bloomington: Indiana University Press, 2015. <https://login.proxy.libraries.rutgers.edu/login?url=https://search.ebscohost.com/login.aspx?direct=true&db=nlebk&AN=1361657&site=eds-live>.
[^fn2]: For guidance, see pp. 9-10 in the College Art Association. “Code of Best Practices in Fair Use  for the Visual Arts,” February, 2015. <http://www.collegeart.org/pdf/fair-use/best-practices-fair-use-visual-arts.pdf>.

