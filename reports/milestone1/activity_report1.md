# Activity Report 1

> Author: Tien Ly  
> Created: June 2024

## Date
Date range: 06/03/2024 - 06/14/2024

## Introduction
As part of milestone 1 of my project as a Satellite Data Scientist Intern at NOAA PolarWatch, this activity report summarizes the tasks I completed during the first 2 weeks of my internship.

## Activities Completed

### Activity 1: Satellite Course
Through the NOAA CoastWatch Learning Portal, I watched a selection of recorded lectures on various satellite products, including sea ice and sea surface temperature, as well as tutorials on the tools used to access satellite datasets. While watching these lectures, I took detailed notes, which helped me solidify my understanding of the material. This activity provided me with a foundational knowledge of satellite products, their applications, and the tools required to effectively utilize satellite data. Through these lectures, I gained valuable insights into how satellite data is processed and how it can be applied to real-world scenarios, enhancing my overall competence in handling satellite datasets.

### Activity 2: Python Tutorials
To familiarize myself with accessing and manipulating satellite data from the CoastWatch ERDDAP data servers, I completed a series of Python tutorials available on CoastWatch's GitHub repository. First, I set up a conda environment called "polarwatch" using a provided YML file. I completed 4 tutorials, including "tutorial1-basics," "tutorial2-timeseries-compare-sensors," "calculate-seaice-extent," and "map-data-with-different-projections." These tutorials are all in the format of Jupyter notebooks, and I ensured that the kernel selected was the polarwatch environment. Here are the descriptions of each tutorial:

- tutorial1-basics: Learn to access satellite data from the CoastWatch ERDDAP data server and work with NetCDF files. Visualize sea surface temperature on a map and plot time-series data.
- tutorial2-timeseries-compare-sensors: Learn common ways to download data from ERDDAP servers to access time-series chlorophyll data from four different satellite datasets, and summarize and visualize the data for comparison.
- calculate-seaice-extent: View sea ice concentration (SIC) data on a map with the polar stereographic projection. Calculate and compare sea ice area/extent from multi-year SIC datasets.
- map-data-with-different-projections: Download and examine a polar stereographic projected dataset, plot the data on a projected map, and add animal track data with geographical coordinates onto the projected map.

Through these tutorials, I learned how to use the xarray package to work with NetCDF files, cartopy for mapping, and matplotlib to create various plots such as time-series plots. I also learned how to read an ERDDAP data request URL and use it in conjunction with the xarray package to download a satellite dataset as a NetCDF file and load the file into Python. Additionally, I gained an understanding of different map projections and how to work with data from various projections.

These tutorials taught me essential skills for handling satellite data.

### Activity 3: Reports and GitHub
I completed detailed reports summarizing what I learned and accomplished during milestone 1 using Markdown. Since I did not have much experience with Markdown, this was a valuable learning opportunity. After finalizing the reports, I organized and uploaded my Jupyter notebooks and reports to a GitHub repository. This process involved several key Git commands that helped refresh my understanding and proficiency with version control using Git.

## Conclusion
In conclusion, completing milestone 1 provided me with a foundational understanding of satellite products and the skills necessary to handle them effectively. I learned how to access satellite data through the ERDDAP data server and became proficient with common Python packages for manipulating this data. Additionally, I gained experience using Git and GitHub as collaborative and project management tools, enhancing my ability to manage version control and contribute to team projects efficiently. I also gained practical experience using conda for environment management and Markdown for documentation.