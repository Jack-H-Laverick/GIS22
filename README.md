# GIS22 :world_map:  :desktop_computer:

Welcome to an Introduction to mapping in R. This workshop assumes a basic familiarity with R and aims to show how you might use open source software for some of the tasks you might instead do in dedicated mapping software such as ArcGIS. 

As we'll be nudging 100 participants on a virtual workshop, this is going to take the form of a code-along rather than a class. We'll be interacting with a web-based bookdown document which contains code and examples. I will work through these on a shared screen by copying code from the site. You can either observe, or If you want, you can copy the code as well and run locally on your machine as we go.

If you choose to code, then create a directory for an R project with Data, R scripts, and Figures folders. If everyone uses the same set up, the code from the website should run locally on your machine without need to edit. You will also need to download the example data and move them into the `./Data` directory. You should end up with the following:

``` bash
.
├── Data
│   ├── Anonymised_AIS_Derived_Track_Lines_2015_MMO
│   ├── ICES_Areas
│   └── RNLI.csv
├── R scripts
├── Figures
└── GIS.Rproj
```
Once you have a project set up, make sure you have installed the latest versions of R and Rstudio, and the following packages: {tidyverse}, {raster}, {sf}, {stars} {sdmpredictors}. You can download the datasets at:

http://s3-eu-west-1.amazonaws.com/mmo-data/MMO_Data/datagovuk/Anonymised_AIS_Derived_Track_Lines_2015_MMO.zip

http://www.fao.org:80/figis/geoserver/area/ows?service=WFS&request=GetFeature&version=1.0.0&typeName=area:FAO_AREAS&outputFormat=SHAPE-ZIP

https://data-rnli.opendata.arcgis.com/datasets/rnli-lifeboat-station-locations/explore?location=54.733404%2C-4.267735%2C6.04
* For the RNLI data download the station locations in .csv format.

This github repo supports the website we will follow during the workshop: https://jack-h-laverick.github.io/GIS22/
The website will be taken down in a few months, so I advise you copy the code into your own scripts and take notes as comments. If you need any help once the website has gone offline you can reach me at jack.laverick@strath.ac.uk. 
