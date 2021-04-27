# 4E-Capstone-Project
> This is an academic project completed by students of the University of Pittsburgh's MS in Quantitative Economics program, advised by Pittsburgh consulting firm Fourth Economy. We use data ranging from 2008-2017 to show how higher unemployment and housing affordability gaps leads to higher rates of evictions, and how this effect is different across counties with different rurality or racial breakdowns.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Repo Documentation](#git-documentation)
* [Status](#status)
* [Contact](#contact)

## General info
The Covid-19 global pandemic has brought about a wave of joblessness and housing insecurity for millions of American families. This analysis aims to explore the extent to which this negative unemployment shock causes housing displacement among renters in all US counties, specifically in counties that were already facing housing shortages prior to the pandemic.

## Technologies
* Analysis built within Jupyter Notebook - R 4.0 Kernel
* Interactive chloropleth map - Python
* Interactive housing market dashboard - Google Data Studio

## Repo Documentation
Data Files:
* alldata1yr.csv: Contains merged data from [CHAS](https://www.huduser.gov/portal/datasets/cp.html#2006-2017_data), [Eviction Lab](https://evictionlab.org/map/#/2016?geography=states&type=er), [ERS](https://www.ers.usda.gov/), and [ACS](https://www.census.gov/topics/education/school-enrollment.html) in the form of 1-year estimates between 2008-2017.
* alldata5yr.csv: Contains merged data from [CHAS](https://www.huduser.gov/portal/datasets/cp.html#2006-2017_data), [Eviction Lab](https://evictionlab.org/map/#/2016?geography=states&type=er), [ERS](https://www.ers.usda.gov/), and [ACS](https://www.census.gov/topics/education/school-enrollment.html) in the form of 5-year averages for the two periods 2008-2012 and 2013-2017 (this is the data that is used in analysis).
* Data Dictionary.pdf: Complete documentation of all variables within the merged datasets - definitions, calculations, and original naming.
* regresults_17: Regression results for each geography in the 2013-17 period. Includes actual and predicted eviction rates, errors, and results for the hypothetical results in the event of a negative employment shock that made unemployment in each county go up by 10%. 

Analysis Files:
* 4E Capstone Housing Analysis.ipynb: Completed analysis file containing background, descriptions of data, methods, modeling, results, and visualizations. R code can be viewed within the notbook using the "toggle on/off raw code" button. Best viewed vis NBViewer at: https://nbviewer.jupyter.org/github/MasonPutt/4E-Capstone-Project/blob/main/4E%20Capstone%20Housing%20Analysis.ipynb
* Capstone Data Cleaning Counties.Rmd: R Markdown file used to clean and merge datasets. Data downloaded beforehand from the above source links.
* Shortage_map.html: HTML link to chloropleth visualization of housing shortages.

## Status
Project is: _Completed_

## Contact
Created by Pitt MQE sudents Mason Putt (MAP347@pitt.edu), Natalee Morris (NSM30@pitt.edu), and Gayatri Pai (GAP54@pitt.edu) - feel free to contact us!
