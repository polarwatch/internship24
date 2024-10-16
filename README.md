# 2024  Summer Internship at PolarWatch

## Internship (Satellite Data Scientist) Details
* Intern: Tien Ly from San Jose State University
* Mentor: Sunny Hospital from PolarWatch
* Start Date: June 3, 2024 (Mon)
* End Date: August 16, 2024 (Fri)
* Project Repository: https://github.com/polarwatch/internship24/
* Communication:
  * Daily check-in via Google Workspace  *Today I will work on ..., Tomorrow I will work on ..., I had issues on ..*
  * 30 minute video check-in on Mondays and Fridays to talk about progress, issues, adjustments, etc.
    * Mondays to focus on technical work discussion
    * Fridays to focus on culture and constructive criticism/advice/discussion for mentor and student
  * Bi-weekly PolarWatch team meeting to meet the team, updates, etc.
* Project Management : GitHub issues 
* NOAA Coastwatch seminar series 
 
## Project Milestone and activities

## Milestone 1 ( 2 wks: 06.03 - 06.14)

__Objective__  You will learn how to use ERDDAP data server, satellite data, python package xarray.

__Activities__
* Satellite course indicated in resource section
  * Satellite 101
  * Sea Surface Temperature,
  * Sea Ice,
  * Sea Surface Height, Winds, Salinity,
  * Tools & Strategy (excl R and ArcGIS)
* Installation of python and required packages
  * conda, python, and required packages provided in requirements.yaml from mentor
* Complete some python tutorials from coastwatch [training github](https://github.com/coastwatch-training/CoastWatch-Tutorials)
  * Setting up a Python environment
  * Tutorial-1
  * Tutorial-2
  * map-data-with-different-projections
  * calculate-seaice-extent
  
__Deliverables__
* Set up conda environment using environment.yml file
* GitHub - use of `git clone`, `git pull`, `git push`, `git branch [your_branch]`, submission of pull request
* Add Jupyter notebooks to the `notebooks/` directory (showing python code used for the satellite course)
* Add course summary (summary of what you’ve learn) to the `reports/milestone1/` directory
* Add Activity report (briefly describing what you have done) to the `reports/milestone1/` directory

## Milestone 2 (3 wks: 06.17 - 07.05) 

__Objective__ 
You will learn about one sea ice data from PolarWatch(sea ice concentration, thickness, IMS, etc.).

__Activities__
* Learn [Polarwatch catalog](https://polarwatch.noaa.gov/)
* Learn about how the data of your choice is developed
* Learn to [read metadata and describe the data product based on the metadata](https://github.com/polarwatch/code-gallery/tree/main/working-with-sea-ice-conc-data) 
* Literature review - find 3-5 journals on how the data are used in research or application and mentor/intern will select 1 article to read
* Create Python notebook to generate statistical summary and visualization of the data from PolarWatch

__Deliverables__
* Description of the data product
* Summary of the article
* Jupyter notebook with data summary and visualization
* Activity report (briefly describing what you have done)

__Note__
If Tien finds an interesting project and the internship schedule allows, we will try to incorporate modeling component.

## Milestone 3 (3 wks: 07.08 - 07.26)

__Objective__ 
You will learn to compute climatology and visulize data on a polar projected map.
Additional Activity: buidling predictive model using sea ice and machine learning

__Activities__
* Learn climatology of sea ice data
* Complete tutorials to [learn how to comptue climatology](https://www.linkedin.com/pulse/python-climate-data-analysis-tutorial-code-ali-ahmadalipour/) [climatology](https://climate.usu.edu/people/yoshi/pyclm101/monthly.html#anomalies-and-climatology)
* Download data and compute climatology of your sea ice data
* Draft Jupyter notebook with explanation
* Draft a presentation and present data summary to the team


__Deliverables__

* Jupyter notebook
* Data summary report
* Activity report (briefly describing what you have done)


## Milestone 4a (2 wks: 07.29 - 08.09)

__Objective__
You will learn to model sea ice prediction using machine learning (deep learning) apporach. We will replicate the model introduced in the [paper] (https://s3.us-east-1.amazonaws.com/climate-change-ai/papers/icml2021/50/paper.pdf)

  * Read journal article: https://s3.us-east-1.amazonaws.com/climate-change-ai/papers/icml2021/50/paper.pdf
  * Create python notebook to build the predictive model using sea ice data from PolarWatch and LSTM algorithm
  * Git repo: https://github.com/big-data-lab-umbc/sea-ice-prediction/tree/main/climate-change-ai-workshop


## Milestone 4b (1 wks: 08.10 - 08.16)

__Objective__ 
You will learn to draft all your work in Quarto and publish in github.io 
https://quarto.org/docs/gallery/

__Activities__
* Design and develop a project website
* Set up quarto/python
* Draft a method page for your data and analysis
* Deploy project on github.io
* Give the project presentation to the team
  
__Deliverables__

* Deployment of the webpage
* Presentation of the project
* Final report

## Resources

* [CoastWatch Lectures](https://umd.instructure.com/courses/1336575)
* [CoastWatch Tutorials](https://github.com/coastwatch-training/CoastWatch-Tutorials)
* [PolarWatch Code Gallery](https://github.com/polarwatch/code-gallery)
