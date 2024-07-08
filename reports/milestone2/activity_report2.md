# Activity Report 2

> Author: Tien Ly  
> Created: July 2024

## Date
Date range: 06/17/2024 - 07/05/2024

## Introduction
This activity report outlines the tasks I completed for milestone 2 of my Satellite Data Scientist internship at NOAA PolarWatch.

## Activities Completed

### Activity 1: PolarWatch Catalog and Sea Ice Concentration Dataset
I explored the PolarWatch website, focusing on its data catalog, which offers a user-friendly interface for examining and downloading satellite datasets, in contrast to the older interface of the ERDDAP website. During my review, I noted several questions which I later discussed with my mentor, Sunny Hospital. 

Together, we selected the **Sea Ice Concentration, NOAA/NSIDC Climate Data Record V4, Northern Hemisphere, 25km, Science Quality, 1978-Present, Monthly** dataset for further analysis due to its relevance to climate change and its numerous applications. Sunny provided a detailed walkthrough of this dataset to ensure I understood its contents and usage. To demonstrate my understanding, I created a document describing the dataset.

### Activity 2: Literature Review
To gain a deeper understanding of sea ice concentration (SIC) and its applications, I conducted a literature review by exploring various peer-reviewed journals and articles related to SIC. I selected and read in detail the following 5 articles:

- [Climate warming and the loss of sea ice: the impact of sea-ice variability on the southeastern Bering Sea pelagic ecosystem](https://doi.org/10.1093/icesjms/fsaa206)
- [Effect of sea ice retreat on marine aerosol emissions in the Southern Ocean, Antarctica](https://doi.org/10.1016/j.scitotenv.2020.140773)
- [Oceanographic factors determining the distribution of nutrients and primary production in the subpolar Southern Ocean](https://doi.org/10.1016/j.pocean.2024.103266)
- [A Data-Driven Deep Learning Model for Weekly Sea Ice Concentration Prediction of the Pan-Arctic During the Melting Season](https://doi.org/10.1109/TGRS.2022.3177600)
- [Seasonal Arctic sea ice forecasting with probabilistic deep learning](https://doi.org/10.1038/s41467-021-25257-4)

Through reading these articles, I gained a better understanding of how SIC data is utilized in research, the significance of sea ice, its effects on ecosystems, and the development of models to predict future SIC data. 

Sunny and I discussed the "Effect of sea ice retreat on marine aerosol emissions in the Southern Ocean, Antarctica" article in detail. We examined the visualizations produced in the paper and considered them as examples for my internship, where the goal is to create visualizations to support researchers. I also learned that SIC data is often used in combination with other types of measurements and data for comprehensive analysis. Finally, I summarized the insights from the article in a document.

### Activity 3: Python Jupyter Notebooks
To learn how to examine and understand a dataset's metadata, I completed the "working-with-sea-ice-conc-data" Python tutorial created by Sunny. This tutorial taught me how to download data from the PolarWatch catalog (instead of the ERDDAP website) and how to access metadata and variable data of a dataset using the xarray library. 

After completing the tutorial, I applied my knowledge by creating a Python Jupyter notebook from scratch to practice satellite data analysis using the previously mentioned SIC dataset. The notebook is divided into two parts:

1. **Time Series Analysis of Sea Ice Concentration in the Arctic (2023):** This section presents an analysis of the monthly mean SIC.

2. **Mapping Satellite Sea Ice Concentration and In Situ Sea Surface Temperature (September 2023):** This section integrates satellite-derived polar stereographic SIC data with geographically referenced in situ sea surface temperature (SST) measurements from the International Arctic Buoy Programme.

This activity allowed me to consolidate my learning and gain practical experience in satellite data analysis and visualization.

### Conclusion
Throughout milestone 2, I have gained valuable skills in satellite data analysis and visualization. By exploring the PolarWatch data catalog and studying the Sea Ice Concentration dataset, I developed a solid understanding of how to navigate and utilize the PolarWatch website. My literature review expanded my knowledge of SIC and its various applications, highlighting the importance of integrating SIC data with other measurements. Completing Python tutorials and creating my own Jupyter notebook allowed me to apply theoretical knowledge to practical tasks. I learned to download and handle satellite data, access and interpret metadata, and perform comprehensive analyses using the xarray library. Additionally, I enhanced my ability to visualize temporal and spatial data, crucial for aiding researchers in their studies. Regular use of Markdown and GitHub further enhanced my skills in documentation and version control. Overall, these activities have equipped me with a strong foundation in satellite data analysis, preparing me for more advanced tasks in my internship.