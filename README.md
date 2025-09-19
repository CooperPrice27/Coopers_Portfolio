## Yellowstone Wildfire Risk LEGO 
![](/Images/CooperPriceWorkSample2.png)

### This map was created as my final project in my Cartography class in Fall 2024, I've always had a strong interest in using GIS for wildlife analysis. 

In this project I pulled in a myraid of data from LANDFIRE, the NLCD, and the National Parks Service. The workflow consisted of: 

- Building a tessellation across the park
- Construction various raster layers based on different variables of fire risk
    - Promiximity to roads
    - Vegetation class and bulk density
    - Slope and ascept

Ultimately, assigning a risk factor from 1-5 based on the fire risk variables, and performing a raster sum on all the previous layers to get a finaly risk talley for each cell in the tessellation 

Continued by adding on a lego style in ArcGIS Pro, using ESRI's remixer and then continued to refine the symbology in Adobe Illustrator:
- Polishing the lego typeface and adding the labels
- Legend design
- Creating the state boarders

## Michigan Internet Access 
![](/Images/CooperPriceWorkSample3.png)
![](/Images/CooperPriceWorkSample4.png)

### These maps were also created as part of my Cartography class in Fall 2024, looking at internet access and supplemental nutrition assistance program (SNAP)

The data for these maps was pulled in from the American Community Survey done by the US Census, which was then brought into Python to do the following:

- Clean up dataframes of unnecessary info, and normalized data by households
- Spatially join census CSV data with Michigan county shapefiles

After exporting the data, using ArcGIS Pro and Illustrator I was to:

- Apply choropleth and proportional symbology
- Designing legends and adding labels 

## PFAS Research
![](/Images/DualMap4.2.png)

### Through my research with Penn State Extension, I've looked at water quality in roadside springs, and the link that has to surrounding land use

The points in these maps represented roadside springs analyzed in our research

- Sites were sampled by various research team members
- Sites tested for various contaminats of emerging concern (CEC)
    - PFAS, pesticide, personal care products, and pharmaceuticals. 

Spatial analysis consistented of
- Creating geodataframes in Python by joining lab testing result spreadsheets with roadside spring point location files
- Buffering the springs, clipping land cover data, and tabulating land cover types
- Applied bivaret symbology, and intricate legend design 

### The findings from this research were also compiled in an [online web map](https://extension.psu.edu/roadside-springs-map)
![](/Images/WebMap.png)

Developed a public-facing web map for Penn State Extension 
- Designed for public accessibility, enabling roadside spring users to explore sampling results across Pennsylvania
- Included dynamic pop-up displays for key contaminants (e.g., PFAS, pesticides) at each site

Developed Arcade scripting skills for advanced customization
- Wrote expressions to real-time water quality metrics with data driven symbology
- Customized pop-up content and attribute expressions based on contaminant thresholds

## Community Mapping for Pollinator Pathways
![](/Images/SubwayLayout7_10-01.png)

### Project Context

- This map was designed as part of Community Mapping Day Event, hosted as a collaberation betweeen the PSU GeoGraphics lab and Easttown Township
- The focus of the day was to highlight Easttown townships pollinator pathways work, goals centered around building green infrastructure, planting new gardens, working with community members to support pollinator habitat, etc.

### Design Process

- My end in the Community Mapping Day was...
    - To create some kind of spatial graphic that would illustrator a potential path for pollinator gardens from Easttown Townnship to metro Philadelphia
- Steps taken throughout the day to complete this transit style graphic were
    - Filtering all the parks/green spaces that did not have pollinator garden devoate space
    - Routing those parks along distances pollinators can cover
    - Styling it all to a SEPTA-inspried transportation graphic

## Millbrook Marsh, Lego Maps
![](/Images/MillbrookStuffCombined.pmng)


### These maps were designed for the Millbrook Marsh Visitor Center, through the GeoGraphics Lab

- The goal of this was to create something that a younger audience could relate and understand with
    - We also wanted something tactile that would encourgae interaction between the map and the audience
 - We reached these goals through the use of Legos

### Design Process

- The map on the right was designed in ArcGIS pro, based on the satellite imagery of millbrook, then using the remixer function to assign lego like design to the major land use types
- Then maps on the left were built using brick link studio, a 3D lego modeling software, to get a life-like view into what a final model would look like


## Mukuru, Nairobi Village Research
![](/Images/OverviewFINAL6_29.png)
![](/Images/IndividualVillages6_29_2.png)

### Project Context

- These maps were created to support a graduate research project focused on urban resilience in Nairobi’s Mukuru informal settlements, where flood risks, political marginalization, and land-use conflicts intersect
- The research examined how unequal power dynamics shape climate adaptation efforts in informal communitie
    - The project required large-format, field-ready maps that could serve as mediums for annotation by participants during interviews

- Initially, the maps were to be printed did not fit the requirements of the project
- At the recommendation of our lab manager, I stepped in to redesign them using ArcGIS Pro and Adobe Illustrator to create clearer, more informative, and professional-quality village and regional overview maps

### Design Note

- This set—11 village-level maps and 2 overview maps—was produced on a very tight turnaround (approximately 10 hours over a day and a half)
- While the final maps reflect a strong effort within those constraints, They reflect both the constraints of time and the practical, fast-paced cartographic support often expected of student workers in cartographic research environments

## Black Bear Hunting Map
![](/Images/BBharvest6_29)

### Project Context

- This map was designed as a passion project, to explore designing maps in Blender, a 3D modeling software
    - Blender is typically used for 3D design and animation, but recently has become more popular for cartographic map design
    - Combined traditional cartographic techniques with a choropleth map, then pushed it further by using non-traditional software to introduce height as an uncommon explored design element





