# Satellite Course Summary

> Author: Tien Ly  
> Created: June 2024

## Introduction
As part of milestone 1 of my project as a Satellite Data Scientist Intern at NOAA PolarWatch, this document summarizes the knowledge I have gained through watching lectures available on the NOAA CoastWatch Learning Portal.

## Topics Learned

### Topic 1: Satellite 101, Part 1
- Types of oceanographic measurements made by satellites
- Benefits of satellite data
- Types of orbits: polar-orbiting satellites vs. geostationary satellites
  - Higher spatial resolution generally means lower temporal resolution, and vice-versa.
- Different resolutions and spatial coverages:
  - Spatial resolution
  - Temporal resolution
  - Spectral resolution
  - Swath width
- Levels of data processing (0-4)
  - Cloud masking
  - Anomaly products and climatologies
  - Composite products are the best way to deal with missing data due to cloud coverage.

### Topic 2: Satellite 101, Part 2
- Electromagnetic radiation (EMR)
  - Satellites measure EMR.
  - Processes alter the EMR signal as it passes through the atmosphere.
  - Emissivity
- Atmospheric windows
  - Satellites can ‘see’ the Earth in the regions of high atmospheric transmittance.
- Atmospheric correction
- How signal collected by sensors becomes information
  - A lot of different processes that affect EMR need to be accounted for and corrected for, in order to get accurate measurements.
- Passive vs. active sensors
- Science quality vs. near real-time (NRT) products

### Topic 3: Sea Surface Temperature
- What is sea surface temperature (SST)?
  - SSTskin
  - SSTsubskin
  - SSTfnd
- Which SST is measured from space?
  - SST can be measured in both the infrared and the microwave.
- Measurements in the infrared
  - Temperature deficit
  -  SST can be measured from space in the infrared, and to obtain accurate measurements, several steps are needed to process the raw data received from satellites.
    - Those steps are: sensor calibration, cloud detection, atmospheric correction, and SST-specific algorithms.
- Measurements in the microwaves
  - Low-intensity signal
  - Diffraction limits spatial resolution.
  - The coast contaminates ocean signals.
  - Sees through clouds
- L4 products

### Topic 4: Sea Surface Height, Winds, Salinity
- Microwave transmission in the atmosphere
- Passive and active satellite sensors
- Sea surface salinity (SSS), wind, and sea surface height (SSH) measurements and products
  - Sea surface salinity is measured with passive sensors.
  - Wind speed (NOT direction) is measured with passive radiometer sensors.
  - Wind speed and direction are measured with active scatterometer sensors.
  - Sea surface height measurements are made with satellite altimeters.

### Topic 5: Sea Ice
- Sea ice properties
  - Sea ice concentration provides the percentage of a grid cell that contains sea ice.
  - Sea ice thickness is the vertical height of the sea ice.
  - Ice type/age refers to first year ice or older multi-year ice which are important distinctions in some research areas.
  - Ice edge products focus on providing the most accurate defining line between sea ice and its surroundings
- Many different satellite sensors can measure sea ice: infrared, microwave, and visible sensors.
- Polar projections

### Topic 6: Tools and Strategy
- Strategies for starting a satellite project
  - Use online satellite data viewers to explore datasets and ocean features
  - Understand file formats and how to visualize file contents
  - Use a good online data servers, for accessing and downloading data
  - Use existing code, software libraries, and software plugins
- Data viewers and file formats
  - Why NetCDF?
  - Software for visualizing NetCDF files: NASA Panoply
- The ERDDAP data server simplifies data access.

## Conclusion
In conclusion, the modules I watched on the NOAA CoastWatch Learning Portal provided me with an overview of the processes involved in creating satellite data products and the foundational knowledge necessary to make informed decisions about selecting a satellite product. These lectures have increased my comfort level with working with satellite datasets, as I had no prior knowledge of satellite data. I now have a basic understanding of satellite products and know where to begin for a simple satellite project, including how to locate and download the data.