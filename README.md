
Purpose

This project explores the earthquake data from USGS.gov for January 1, 2022 to March 31, 2022 with any magnitude 2.5 or greater.  USGS no longer uses the Richter Scale to determine earthquake strength.  The Richter Scale has been determined to be outdated.  Currently the USGS Moment Magnitude Scale, which takes into consideration the stiffness of the rocks, among other measures.     

![Earthquake Magnitude Scale](https://d9-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/thumbnails/image/Mag-Energy-Freq-sm.gif)

Requirements

Python 3.10.5 with 
    numpy, pandas, matplotlib, os, datetime, plotly, geopandas, jupyter notebook

Anaconda3 4.13.0
    
    ##NOTE :  To install GeoPandas please execute the following commands in order at the Anaconda CMD Prompt:

        conda update --all

        once complete:

        conda config --prepend channels conda-forge
        conda create -n geo --strict-channel-priority geopandas jupyterlab

        Next choose the Geo environment and use VS Code to view.

VS Code 1.68.1       