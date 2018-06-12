---
title: "Narrative Mapping: Instructions on Data Assembly"
author: Francesca Giannetti, Digital Humanities Librarian
date: May 30, 2018
mainfont: EB Garamond
fontsize: 11pt
---

<!-- 1. Create a free public account for ESRI's Story Maps at <https://storymaps.arcgis.com/>. You can link it to your Google account, which may be easiest. -->

<!-- pandoc -s -f markdown+smart -V geometry:margin=1in -V urlcolor:Maroon --columns=45 fernandez_narrative-mapping-instructions.md -o fernandez_narrative-mapping-instructions.pdf -->

## Introduction

> A narrative map tells a story plotted through space. The point of a narrative map is not to display data. Rather it is to provide an explicit visual counterpart to the implicit spatial underpinnings of a narrative or argument.[^fn1]

*Note*: This is homework to be completed **before** (!!) our meeting on creating narrative maps.

In our next meeting, we'll work on creating a narrative map of your oral histories. Unlike Social Explorer, which is used for the display of quantitative information, narrative maps are usually more qualitative in their orientation. The tool we will use, [ESRI's Story Maps](https://storymaps.arcgis.com), will help us to create a linear, place-based narrative that can accommodate text, still images, and multimedia embeds. You may wish to include one or more maps you created in Social Explorer, either in the form of a still image or an interactive web map, as a section of your narrative.

In order to have material to work with during our class session, please prepare the following ahead of time. It's okay if you're uncertain of what to include at this point. The main purpose of this task is to have some material to work with while learning the tool. 

1. A spreadsheet of location data assembled using the template below.
2. An outline of materials to include for a Main Page (what your reader sees first when they visit your narrative map) and 3-4 Sections (stops on your narrative). 

## Location Data

Not every section of your narrative map has to be associated with a location, but it's decent starting point. And it is easier to create the sections of your narrative map when you have a pre-prepared spreadsheet of locations of importance to your oral history. Please create a Google Sheet with the following field names:

- **name**: A location caption for the map marker. The name can include multiple words, and will wrap to a second line if necessary.
- **description**: A short description of why this location is important to your narrative. It should be kept to 1-2 short sentences, and may be something you write or a direct quotation from your oral history.
- **lat**: the latitude (Y) coordinate in decimal degrees.
- **long**: the longitude (X) coordinate in decimal degrees.

How do I find the latitude and longitude coordinates of my location? There are lots of ways to go about it, but I think the easiest is to look it up using <https://www.latlong.net/>.

Example drawn from: "When people got together and there were feasts: Recollections of Tom Olivieri." In _Vanishing Hoboken: The Hoboken Oral History Project_, 1-21. Hoboken: Hoboken Historical Museum, 2005.

| name | description | lat | long |
|---------------|---------------------------------|------------|-------------|
| Corsica | "My grandfather was born in Corsica, and for one reason or another he wound up in Puerto Rico in the early 1800s." (p. 2) | 42.039604 | 9.012893 |
| Cataño | "...the town we lived in last, Catano \[...\] was more rural, even though it was only a ferryboat ride away from San Juan." (p. 3) | 18.446535 | -66.135578 |
| New York | "We lived in New York three months prior to coming to Hoboken \[...\] in what is now known as Washington Heights, 166th Street and Amsterdam Avenue." (p. 4) | 40.838704 | -73.937785 |
| Willow Avenue | "I was raised right here on Willow Avenue, in what used to be known then as the 'Tootsie Roll Flats.'" (p. 5) | 40.747928 | -74.031511 |

## Section Outline

In addition to your location data, you will want to have a rough draft of the sections of your narrative map. Each section may include: a short text, images, videos, image/video captions, links to external resources, and maps. 

We will use ESRI's "Map Journal" app to create our narrative map, which allows us to present a narrative as a scrolling side panel that floats on top of a map or image.[^fn2] The "Map Journal" asks that each section be organized as a "side panel" and "main stage" that occupy one third and two thirds of the screen, respectively (although you can tweak the widths). 

Again, using Olivieri's oral history as an example, a corresponding section outline might look like this:

- Main Page
    + Title: Tom Olivieri's Story
    + Side panel: "A tenant's rights activist, and later, a cultural affairs official for the city, Mr. Olivieri has long been at the center of cultural and civic activities in Hoboken's broad-ranging Hispanic community..." (p. 1)
    + Main stage: overview map showing all the important locations in his oral history
- Section 1
    + Title: Grandfather
    + Side panel: "My grandfather was born in Corsica, and for one reason or another he wound up in Puerto Rico in the early 1800s." (p. 2)
    + Main stage: map zoomed to Corsica
- Section 2
    + Title: Cataño
    + Side panel: "...the town we lived in last, Cataño [...] was more rural, even though it was only a ferryboat ride away from San Juan." (p. 3) + "Cataño" by Juan Cristobal Zulueta, <https://www.flickr.com/photos/28312366@N08/15313419317/sizes/l>
    + Main stage: map zoomed to Cataño
- Section 3
    + Title: New York
    + Side panel: \[...\] + "Manhattan: 166th Street (West) - Amsterdam Avenue" by Percy Loomis Sperr, <http://digitalcollections.nypl.org/items/510d47dd-1ba2-a3d9-e040-e00a18064a99>
    + Main stage: \[...\]
- Section 4
    + \[...\]

## Attribution

Consider your story map a form of scholarly web publication. It won't be as text-centric as a traditional essay, but notions of academic integrity should still govern your use of any material that you did not yourself create. This includes textual references or quotations, as well as still images, video, data, and maps. Out of consideration of the form, you may not want to include footnotes or a formal reference list, but you should include information about author, title, and date (where available), and source in a caption. If you can link to the source online, do so. This practice not only helps your reader understand and refer back to your original sources, it also allows the creators of the reused content to get credit for their work. 

Furthermore, since you will need to make your story map public on the web in order to share it with your professor and others, there's a small but non-zero chance that your work might get discovered by the creators of the reused content. In order to defend your work against claims of copyright infringement, look for works that are either in the public domain (often denoted as PD or CC0) or licensed for reuse (e.g. CC BY). Given the scholarly nature of this assignment, you will want to ensure that your reuse of others' work is in support of a point or argument you are making. In other words, **not** for mere visual interest or decoration. We'll talk more in person about how to find such works and what to do in the absence of any clear license or permission. For now, you might consult April Hathcock's guide to reusing images at <https://guides.nyu.edu/copyright/images>.  

## Examples for study

When embarking on anything new, most of us are aided by the study of good examples. You may find these to be helpful to get a sense of what is possible:

- Maryland Historical Trust: Maryland Women's Fight for the Vote, <http://maryland.maps.arcgis.com/apps/MapTour/index.html?appid=b645f981cc66484289099cac9d4348a1>
- Philadelphia Water Department, A Virtual Walking Tour: Cobbs Creek Green Improvements, <http://phl-water.maps.arcgis.com/apps/MapJournal/index.html?appid=c68733f61bab44a4be0470995809566f>
- New York City Landmarks Preservation, Taking Pride, <http://nyclpc.maps.arcgis.com/apps/MapJournal/index.html?appid=f56a0b10ac214b0a97f1cb7934f8ef49>

See the Story Maps Gallery at <https://storymaps.arcgis.com/en/gallery/> for more.

[^fn1]: Lincoln Mullen, "Spatial Humanities Workshop: Narrative Maps," <https://lincolnmullen.com/projects/spatial-workshop/narrative-maps.html>.
[^fn2]: The "Map Tour" and "Cascade" apps are additional possibilities that support narrative arguments; you may want to investigate those on your own time.