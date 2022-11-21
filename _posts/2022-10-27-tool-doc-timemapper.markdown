---
layout: post
title: "Tool Documentation: TimeMapper"
date: 2022-10-27
description: This is an introduction to the web based tool, TimeMapper, and includes a step by step guide to creating your first project.  # Add post description (optional)
img: timemapper-map.png  # Add image post (optional)
tags: [timemapper, interactive, timeline, map, digital exhibit] # add tag
---
**Introduction**

[TimeMapper][timemapper] is an open-source web tool that allows users to visualise data in an interactive map, timeline, and info panel. Images, dates, text, and geolocation are all customizable and a template spreadsheet provided by TimeMapper makes it easy to prepare data for upload. This tool is very accessible as it is browser-based and requires no installation or specialised hardware. 

**Installation + Environmental Setup**

As mentioned, no software needs to be installed on your computer to use TimeMapper. All data is prepared in Google Sheets and uploaded into the TimeMapper browser interface where editing and customization can be completed. 

Creating a Google account is necessary to use Sheets, which is free and can be done [here][googleaccount]. Further, a TimeMapper account is not necessary but is recommended. Proceeding without an account will result in your project being created anonymously and comes with less control once your project is published. Projects created within a TimeMapper account allow the user to delete, edit, and organise their projects, and allow the user to personalise the URL for the project. You can create an account and log in using your Twitter. 

To access the Google Sheets template created by TimeMapper see [here][tm_temp]. Save a copy to your Google Drive so you know everything is saved and accessible in the future. There are instructions below on how to do this. Also, there are instructions at the top of each column, read them for notes on inputting data. 

**Features**

Maps
Include pinned locations with tags using geodata (longitude and longitude).
Create boundaries using GeoJSON objects (creates an outline around an area).
Maps are interactive, users can zoom in and out, move, and reveal information by clicking points.

Timeline
Dates can be plotted on the timeline (Eg. Prolonged events such as a person's lifespan, or a single day).
The timeline is interactive, allowing the user to scroll, zoom, and interact with the nodes and events.

Info Panel
Present images, text, dates, tags, and more.
This window scrolls page to page and is coordinated with the timeline and map.

**Examples**

_**First Steps**_

Once you have decided to log in or work anonymously, you can start by viewing the Google Sheets template provided by TimeMapper. First, it is best to add a shortcut of the [template][tm_temp] to your Google Drive and then save a copy, which will allow you to edit.

Add a shortcut to your Drive: File> Add a shortcut to Drive> Select the location in Drive and click Add Shortcut.

Make a copy to edit: File> Make a copy> Change the file name, select the folder you want to save it in and click Make a copy.

<image src="/assets/img/save_a_copy.gif" alt="An animated GIF showing step by step how to save a copy of a Google Sheets document in your personal Google Drive" width="450" />
![An animated GIF showing step by step how to save a copy of a Google Sheets document in your personal Google Drive](/assets/img/save_a_copy.gif)

This is now the file that you can use for this project. Each time you start a new project make a copy of the original and rename it. 

_**Create a Simple Map**_ 

Using the Google Sheets template from TimeMapper, you can choose to only input certain details that pertain to the map or timeline. In this example, only the Title and Location are essential to creating a basic map with pinned locations.

See the spreadsheet we will use below. 

img: 7wonders-maponly_sheet.png

For historic sites, research may be needed to find accurate geographic information. For this project, the coordinates were found on [Wikipedia][wiki7wonders]. The simplest way to find most modern coordinates is via Google Maps. See below.

Step 1: Open Google Maps and search the place. 
Step 2: Right-click on the marker for the place and click the longitude and longitude coordinates. The coordinates are now copied. 
Step 3: Paste them into the spreadsheet under the Location column.

img: getting_coordinates.gif 

Once data input is complete it is time to prepare for uploading the spreadsheet to TimeMapper. First, you need to publish the spreadsheet to the web. This will make the data in the spreadsheet viewable by TimeMapper. 

To do this: File> Share> Publish to web> click Publish> then copy the link provided

img: Publish_to_web.gif

Now let’s move over to [TimeMapper][timemappercreate] and put this data to use. 

Step 1: Sign in (if you choose to).
Step 2: Paste the link to your spreadsheet next to Data Source.
Step 3: Type in your page title and (if you’re signed in) the URL you would like to use. 
Step 4: Select the data view. In this case, we want to select Map. 
Step 5: Click Publish.

img: Map_only-TimeMapper.gif

[Here][maponly] is a link to what we created. Easy right?

**A Full Project**

The next example will show the full breadth of TimeMapper, which includes an interactive map, timeline, and info panel. For the most part the process is the same, there are just a couple of extra things to be mindful of. They are:

Date format
mm/dd/yyyy OR dd/mm/yyyy are acceptable. Be consistent and be sure to select the format you used in the customising menu. 
Are you only putting in the year? For dates that occurred BCE include a “-” symbol before the year (eg. -1200, not 1200 BCE). 

Start Point
Where would you like the project to start? There are three options: 
First event 
Last event 
or Today. 
This selection will set the point in which the viewer begins.

[Here][fullproject] is the example spreadsheet that is published to the web for this project. You’ll see that it holds far more data and TimeMapper does an excellent job of coherently visualising this extra information. 

Follow the same steps as above and create this project. Then take a look at how the data provided is presented. You can see it here: [7 Ancient Wonders of the World][7wonderfull]. 

**Making edits**

Once the project is published there are only a few edits that can be made from within TimeMapper. This includes changing the visualisation type, date handling, and the starting place for the timeline. Edits to the Google Sheets document will continue to update automatically. So if data needs to be changed or updated this can be done by editing the spreadsheet directly. The changes will be reflected the next time the TimeMapper page is opened or refreshed. 

[timemapper]: https://timemapper.okfnlabs.org/ 
[googleaccount]: https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp
[tm_temp]: https://docs.google.com/spreadsheets/d/1LlYBnfhvD3ZUXMGZ8e52UwYp-xn_NeWmaGBx7VBz5V8/edit#gid=0
[wiki7wonders]: https://en.wikipedia.org/wiki/Seven_Wonders_of_the_Ancient_World
[timemappercreate]: https://timemapper.okfnlabs.org/create
[maponly]: https://timemapper.okfnlabs.org/rrrivando/maponly#2 
[fullproject]: https://timemapper.okfnlabs.org/rrrivando/maponly#2
[7wonderfull]: https://timemapper.okfnlabs.org/rrrivando/7wondersancientworld#0

