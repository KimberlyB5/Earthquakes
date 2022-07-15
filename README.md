
**Purpose**

This project explores the earthquake data from USGS.gov for January 1, 2022 to March 31, 2022, with any magnitude 2.5 or greater worldwide.  USGS no longer uses the Richter Scale to determine earthquake strength.  Currently the USGS Moment Magnitude Scale, which takes into consideration the stiffness of the rocks, among other measures.  In the first quarter of 2022, there were 7,020 earthquakes worldwide.  On January 11, 2022, almost 200 earthquakes occured that day.  Most    

![Earthquake Magnitude Scale](https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/thumbnails/image/Mag-Energy-Freq-sm.gif)

Requirements

Python 3.10.5 with 
    numpy, pandas, matplotlib, os, datetime, plotly, geopandas, geopy, geocoder, jupyter notebook

Anaconda3 4.13.0
    
    ##NOTE :  To install GeoPandas please execute the following commands in order at the Anaconda CMD Prompt:

        conda update --all

        once complete:

        conda config --prepend channels conda-forge
        conda create -n geo --strict-channel-priority geopandas jupyterlab

        Next choose the Geo environment and use VS Code to view.

VS Code 1.68.1 with Jupyter extension

#To Use:

1. Make sure you have Anaconda3 updated as shown above and have the geo enviroment.
2. Copy repo Earthquake from github.com   https://github.com/KimberlyB5/Earthquakes.git
3. Open Anaconda3 and select the geo environment and choose VS Code to open the downloaded Earthquake repo.
