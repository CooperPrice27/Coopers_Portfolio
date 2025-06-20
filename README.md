# Cooper's Portfolio

## Yellowstone Wildfire Risk Lego 
![](/Images/CooperPriceWorkSample2.png)

### This map was created as my final project in my Cartography class in Fall 2024, I've always had a strong interest in using GIS for wildlife analysis. 

In this project I pulled in a myraid of data from LANDFIRE, the NLCD, and the National Parks Service. The workflow consisted of: 

- building a tessellation across the park
- construction various raster layers based on different variables of fire risk
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

### These maps were also created as part of my Cartography class in Fall 2024, Looking at internet access and supplemental nutrition assistance program usafe

The data for these maps was pulled in from the American Community Survey done by the US Census, which was then brought into python to do the following:

- Clean up dataframes of unnecessary info, and normalized data by households
- Spatially join census CSV data with Michigan county shapefiles

After exporting the data, using ArcGIS Pro and Illustrator I was to:

- Apply choropleth and proportional symbology
- Designing legends and adding labels 

## PFAS Research Maps
![](/Images/DualMap4.2.png)

### Through my research with Penn State Extension, I've looked at water quality in roadside springs, and the link that has to surrounding land use

The points in these maps represented roadside springs analyzed in our research

- Sites were sampled by various research team members
- Sites tested for various contaminats of emerging concern (CEC)
    - PFAS, pesticide, personal care products, and pharmaceuticals. 

Spatial analysis consistented of
- Creating geodataframes in python by joining lab testing result spreadsheets with roadside spring point location files
- Buffering the springs, clipping land cover data, and tabulating land cover types
- Applied bivaret symbology, and intricate legend design 

### The findings from this research were also compiled in an [online web map](https://extension.psu.edu/roadside-springs-map)
![](/Images/WebMap.png)

Allowing for interested roadside spring users to be able to look at the sampling results of springs across the state

This project gave me great exposure to the ArcGIS online suite, and great learning opportunity for arcade coding language 

## Mukuru Village Maps








