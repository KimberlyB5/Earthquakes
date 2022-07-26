
**Purpose**

This project explores the earthquake data from USGS.gov for January 1, 2022 to March 31, 2022, with any magnitude 2.5 or greater worldwide.  USGS no longer uses the Richter Scale to determine earthquake strength.  Currently the USGS uses Moment Magnitude Scale, which is based on physical properties of an earthquake derived from an analysis of all the waveforms recorded from the shaking[^1].[^1]:United States Geological Survey. Retrieved from https://www.usgs.gov/programs/earthquake-hazards/earthquake-magnitude-energy-release-and-shaking-intensity.  In the first quarter of 2022, there were 7,020 earthquakes worldwide.  On January 11, 2022, almost 200 earthquakes occured that day.   

![Earthquake Magnitude Scale](https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/thumbnails/image/Mag-Energy-Freq-sm.gif)

**Requirements**

Python 3.10.5 with geopandas, matplotlib, os, pandas, plotly

VS Code 1.68.1 with Jupyter extension

Anaconda3 4.13.0
    
NOTE :  To install from the environment.yml at the Anaconda3 Command prompt:

`conda env create -f environment.yml`

once complete:

`conda activate geo`
        
Check the environment: (Make sure geo is there)
        
`conda env list`

Next choose the Geo environment and use VS Code to view.

**To Use:**

1. Copy repo Earthquake from github.com   https://github.com/KimberlyB5/Earthquakes.git
2. Open Anaconda3 and select the geo environment (made above) and choose VS Code to open the downloaded Earthquake repo.
3. Choose Run All to run all the cells.

The following were included for this project:

    1.  CSV data read by Pandas from  https://earthquake.usgs.gov/earthquakes/search/ from 1/1/2022 to 3/31/2022 for Earthquakes
    magnitude 2.5 and above, under Advanced options, Event Type choose Earthquake then CSV output and time - newest first.

    2.  Manipulate and clean data - Copy data file, Seperate date and time, drop NaN in all columns, verify data after dropped NaN

    3.  Analyze the data - with the "mag" column find the mean, mode, and median, with the seperated "date" column find the mode,
    with the "date" column total the unique days that an data occured on, then divide the unique days by the number of days in the quarter
    to get the percentage of days that earthquakes occured on.

    4.  Visualize your data - provided an interactive world map that displays the location and magnitude of each earthquake,
    provided a magnitude color coded world map showing the locations and coordinated magnitude,  provided scatter graph to show which
    magnitudes occur most frequently, provided bar graph to show which days the most earthquakes occured on for the quarter.

   