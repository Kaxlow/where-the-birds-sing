# Data Mining to Find Safe Habitats for Birds
Our team aims to identify the most important factors to consider when choosing where to build a new bird sanctuary in Colorado. Our analysis includes data on bird counts from [eBird](https://documenter.getpostman.com/view/664302/S1ENwy59) as well as external factors such as climate data from [NCEI](https://www.ncdc.noaa.gov/cdo-web/webservices/v2), natural disaster data from [FEMA](https://www.fema.gov/about/openfema/api), and urban population data from the [American Community Survey](https://www.census.gov/programs-surveys/acs/data/data-via-api.html). The goal of the analysis is to finding meaningful patterns and relationships from the data associated with bird counts throughout Colorado at different times of the year, and try to predict the future of bird species in Colorado.

This repository is created to share our findings. Our findings are also available at **[our project website](https://melissazuch.wixsite.com/where-the-birds-sing)**

## The Team
Ken Low - Modeling Lead
Kyla McGregor - Data Lead
Melissa Zuch - Website and Data Visualization Lead

## Project Outline

### Data Gathering
We aim to collect data on bird counts from eBird, one of the largest projects ever to track bird sightings. Climate, natural disaster, and urban data will be gathered from government agencies. 

### Data Preprocessing
Then, the data will be cleaned and preprocessed to improve its accuracy and completeness and ensure that it is in a proper format for analysis.

### Exploratory Data Analysis
Exploratory data analysis will be done to investigate the variables and identify which features to be used for further analysis, performing feature transformations as required. 

### Data Visualization
Visualizations would be created to show insights from the given features. Then, different classes of machine learning models will be run against the preprocessed data for different purposes. 

### Data Modeling
Clustering models can identify geographic regions of interest and groups of bird species with similar characteristics. Classification models can indicate if an area is safe or dangerous, if a species is threatened or not. Regression models can identify the variables that have the strongest relationships with bird count changes in a location. Frequent Pattern Mining can predict the future state of a species.

### Reporting
Finally, we will produce a report containing the findings on which are the most important factors to consider when designating an area as a bird habitat, and the implications of our analysis.