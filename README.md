
![Earthquake Magnitude Scale](https://i.cbc.ca/1.1877835.1380772347!/httpImage/image.jpg_gen/derivatives/original_780/earthquake-magnitude.jpg)



#Purpose

This project explores the earthquake data from USGS.gov for January 1, 2022 to March 31, 2022.  USGS no longer uses the Richter Scale to determine earthquake strength.  The Richter Scale has been determined to be outdated.  Currently the USGS Moment Magnitude Scale, which takes into consideration the stiffness of the rocks, among other measures.     


#Requirements

Python 3.10.4
    numpy, pandas, matplotlib, os, datetime, geopandas
Anaconda3 4.13.0
    
##NOTE :  To install GeoPandas please execute the following commands in order at the Anaconda CMD Prompt:
        conda update --all

        once complete:
        conda config --prepend channels conda-forge
        conda create -n geo --strict-channel-priority geopandas jupyterlab

        Next choose the Geo environment and use VS Code to view.

VS Code 1.68.1        