# Surfs_Up

Module 9 - Weather analysis using SQLite, SQLAlchemy and Flask 

Completed by Angela Kumar

# Purpose

Using Python, SQLite, SQLAlchemy, and Flask; analyze the data and visualize the climate data as preparation to open a surf shop.

# Overview

Using Python, SQLite, SQLAlchemy, and Flask to build on the knowledge of SQL database structures and querying methods. Writing and executing Python code in the Jupyter Notebook and create graphs using Matplotlib.

# Resources

Files: hawaii.sqlite, app.py, climate_analysis.ipynb, SurfsUp_Challenge_starter_code.ipynb changed to Surfs_Up_Challenge.ipynb

Software: Python; SQLite; SQLAlchemy; Flask; VSCode; Anaconda3; Jupyter Notebook

# Background

W. Avy likes the analysis given for precipitation, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.  W.Avy liked the welcome site as well.

<img width="202" alt="screenshot of welcome" src="https://user-images.githubusercontent.com/85860367/130312307-8451ef92-b1f6-4ff6-b9d0-ecf3768b4482.PNG">

<img width="389" alt="Screenshot of precipitation" src="https://user-images.githubusercontent.com/85860367/130313190-a8da8c0c-e45a-4f58-9492-0a7ac829643a.PNG">

<img width="759" alt="screenshot of stations" src="https://user-images.githubusercontent.com/85860367/130313055-9684d59a-7bd2-4ad5-aa9d-752ae2ae7209.PNG">

<img width="585" alt="screenshot of tobs" src="https://user-images.githubusercontent.com/85860367/130313067-1fb7daf5-a826-4cf5-9ee9-a5309b9b8c93.PNG">

<img width="365" alt="screenshot for June min avg max" src="https://user-images.githubusercontent.com/85860367/130313128-c05819c0-5016-4ce1-8c14-e3ed80aee406.PNG">

# Deliverables

### Deliverable 1: Determine the Summary Statistics for June

Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

Download the SurfsUp_Challenge_starter_code.ipynb file into your surfs_up folder, then rename it SurfsUp_Challenge.ipynb.

Use the instructions below to add code where indicated by the numbered comments in the starter code file. The starter code file includes all dependencies needed for this Challenge.

In Step 1, write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of June.

In Step 2, convert the June temperatures to a list.

In Step 3, create a DataFrame from the list of temperatures for the month of June.

In Step 4, generate the summary statistics for the June temperatures DataFrame.

After you run 4 in your SurfsUp_Challenge.ipynb file, confirm that the summary statistics match the image below.

<img width="505" alt="June dataframe" src="https://user-images.githubusercontent.com/85860367/130310886-d1886425-eb5c-4179-8a4e-4045c03179ec.PNG">

### Deliverable 2: Determine the Summary Statistics for December

Use the instructions below to add code where indicated by the numbered comments in your SurfsUp_Challenge.ipynb file.

In Step 6, write a query that filters the date column from the Measurement table to retrieve all the temperatures for the month of December.

In Step 7, convert the December temperatures to a list.

In Step 8, create a DataFrame from the list of temperatures for the month of December.

In Step 9, generate the summary statistics for the December temperatures DataFrame.

After you run Step 9 in your SurfsUp_Challenge.ipynb file, confirm that the summary statistics match the image below.

<img width="534" alt="Dec dataframe" src="https://user-images.githubusercontent.com/85860367/130311039-0ea4ac5b-ba1c-42f8-885f-6339bf207469.PNG">

### Deliverable 3: A written report for the statistical analysis (README.md)

### Purpose of Analysis

Using Python, Pandas functions and methods, and SQLAlchemy, the purpose of the analysis is to filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures and precipitation, then convert those temperatures and precipitation to a list, creating a DataFrame from the list, and eventually generate the summary statistics.  

### Results

* June and December Temperatures:

The average temperature for June is 75, and the average for December is 71.  The standard deviation is about 3.26 and 3.75 respectively between the two given months.

<img width="395" alt="June and December Temperatures" src="https://user-images.githubusercontent.com/85860367/130312229-81a0e116-3b22-4ebe-b4d1-623bbe8c79eb.png">

* June and December Precipitation

The average rainfall for June is .14, and the average for December is approximately .22.  The standard deviation is about .34 and .54 between the two given months.

<img width="350" alt="June and December Precipitation" src="https://user-images.githubusercontent.com/85860367/130312635-8c29f117-43ef-4ea5-b40a-358f495b919d.png">

* Average Temperatures

The average temperature overall in Hawaii is about 75, this aligned with June summer weather.  The standard deviation is about 4.61.  June and December temperatures are less than the overall rate, and it means that there are more days clustered around the mean, and less spread means that the opportunity is stable with warm temperatures.

<img width="137" alt="Average temperatures" src="https://user-images.githubusercontent.com/85860367/130312683-9d68e547-a3c3-434e-bf2d-c8453a08ec35.PNG">

<img width="333" alt="tobs chart" src="https://user-images.githubusercontent.com/85860367/130312692-1c587771-ba16-45c2-bb3b-87e60dad7b72.PNG">

* Average Precipitation

The avarage precipitation overall in Hawaii is about .18, the standard deviation is about about .46.  Again June and December temperatures are less than the Overall rate, and it means that there are more days closer around the mean, the less spread means that there are more days that are filled with sunshine.  Rainfall is usually about 0-2 days on average, there are some days where it is a week or so.
<img width="132" alt="Average precipitation" src="https://user-images.githubusercontent.com/85860367/130312707-7c929f4c-97d3-4c18-9f7f-2201081b04c6.PNG">

<img width="349" alt="Precipitation graph" src="https://user-images.githubusercontent.com/85860367/130312715-f12b01c2-eea7-4d11-9e03-3ddeea78a0a1.PNG">

<img width="400" alt="Output of the station temperatures" src="https://user-images.githubusercontent.com/85860367/130315428-51f3e182-5739-462b-8f56-9d7c1c1bf3c1.png">


### Summary

The analysis indicates that there is not much difference in temperatures between Overall, June and December.  The standard deviation in temperatures and rainfall for June and December are much lower than the Overall rate, and therefore indicates that there are more days closer to the mean.  Lower spread in standard deviation also means that this opportunity is stable and has a lower business risk.
The analysis also indicates that there are more warmer, drier days for surfing and ice cream. It appears that the weather is cooler and rainer during the months of December through March, however the climate is still mild enough for surfers, tourist, and locals. There are more months of favorable weather for water sports, outdoor leisure events and of course ice cream.  Studies show that ice cream sales are better during the winter months as there are more sales, less lines and ice cream meltdowns.  
Of course the main area that was analyzed was Oahu, Hawaii and this is a major hub for tourists, passengers, and locals. It is a business opportunity that is too good to pass up. It would have been good to see some other months such as March and September to see the patterns and trendlines, and if there was an significant variance.  It may have been good to review another location such as Florida or California just to compare if there are other possibilities for the business idea to expand.
 
