# Introduction to QGIS

This workshop will teach you some of the basics of QGIS, an open-source GIS (Geographic Information Systems) tool, using COVID-19 data.

## Getting started

### What do I need to install?

[Install QGIS](https://qgis.org/en/site/forusers/download.html) (Please install the long term release version--this is the most stable version, with the fewest bugs)

[Download workshop files](https://resources-covid19canada.hub.arcgis.com/datasets/health-region-summaries)

You will need a program to unzip the files you download. Depending on your operating system, choose one of the following options:

Windows: [Use File Explorer](https://support.microsoft.com/en-us/windows/zip-and-unzip-files-f6dde0a7-0fec-8294-e1d3-703ed85e7ebc)

Mac OS: [Double click on .zip file](https://support.apple.com/guide/mac-help/zip-and-unzip-files-and-folders-on-mac-mchlp2528/mac) | [The Unarchiver](https://apps.apple.com/us/app/the-unarchiver/id425424353?mt=12)

Linux: [Instructions](https://itsfoss.com/unzip-linux/)

### Why QGIS?

QGIS is an open-source GIS tool. The software and all plugins are free to download. It also runs on all major operating systems, including Windows, Mac OS, and Linux (Ubuntu). The community is active and friendly and the software is in constant development. QGIS is ideal when you want a program that does most of what ArcGIS does, but don't use or have access to a computer running Windows.

## Goals and Objectives

Over the course of this workshop, we will create a map that visualizes COVID-19's spread through Canada by:

- Becoming acquainted with the QGIS interface.
- Learning the difference between raster and vector data.
- Adding data to our QGIS project.
- C

## Opening and navigating QGIS

### Using the interface

## Importing data

QGIS allows you to import multiple data types, including ...

### Understanding vector and raster data types

While there are many kinds of spatial file types, there are two main kinds of data that you'll use when you work with GIS tools. These are called **vector** and **raster** data.

**Vector** data consists of points, lines, and polygons. These are discrete objects. Vector data is precise, but not always accurate.

**Raster** data consists of a collection of scalable but equally-sized cells. You can think of these as pixels on a computer screen: although they may have differing colors, every screen has a certain number of square pixels, all of which are the same size. Raster data can come in the form of a background image or basemap.

Vector data is common in the social sciences, and raster data is common in the environmental sciences. However, this is not a hard and fast rule: many disciplines make use of both.

### Importing data

To import data, navigate to the toolbar and double click on the button that shows blue, yellow, and red squares stacked on top of each other. 

A window called the Data Source Manager will appear. In the sidebar of this window, there are several options for adding data of varying types. 

For now, we will be importing the workshop files that we downloaded earlier, called "Health Region Summaries." The files in the folder that we downloaded contain information about COVID-19's spread through Canada, including COVID-speciifc information (case, death, and recovery counts by province or territory), as well as general information about different provinces and territories (average age being one example). It also contains boundary lines that we can use to make a map of health regions throughout Canada.

The data we are using is vector data. We know this because it is composed of lines, including boundary lines. In the sidebar, click on the option for "Vector." 

Make sure that "Source Type" says "File." Then click on the "..." button next to the search bar to pull up either your File Explorer or a Finder window.

Navigate to the folder you downloaded at the beginning of the lesson, which is titled "Health_Region_Summaries." 

When you select the folder name, you will see that inside the folder are several files which have similar names but different extensions. Today, we will use a shapefile. Select the file "NewHybridRegionalHealthBoundaries.shp." 

In the Data Source Manager window. click "Add" and return to the main screen.

## Adjusting projection

Every map (including "analog" or "IRL" maps) is designed according to a **projection**. Because the Earth is a spherical object, it cannot be represented on a flat surface (such as a map) with 100% accuracy. Projections are changes in the way that maps represent the Earth. 

One of the most well-known projections is the Mercator projection. The Mercator projection distorts the size of areas far from the equator, meaning that these areas appear to be much larger than they actually are. Because of this, we will adjust the projection used in our project to minimize distortion of Northern Canada.

## Changing style

Now that we've imported our data

![Image of Canada, divided by health regions which are colored from light to dark red to represent the amount of reported COVID-19 cases.](/canada-full-final.png)

![Image of Ontario, divided by health regions which are colored from light to dark red to represent the amount of reported COVID-19 cases.](/canada-ontario-final.png)

## Saving and exporting your map

## Additional resources
