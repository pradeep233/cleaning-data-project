# Getting and Cleaning Data

##Project Details
Goal:
project is to demonstrate ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

## Dependencies

```run_analysis.R``` file will help you to install the dependencies automatically. It depends on ```reshape2``` and ```data.table```.


## Steps


1. Refer CodeBook.md for variables used for R script ```run_analysis.R```
2. Download the data source and put into a folder on your local drive. You'll have a ```UCI HAR Dataset``` folder.
3. Put ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```, then set it as your working directory using ```setwd()``` function in RStudio.
4. Run ```source("run_analysis.R")```, then it will generate a new file ```tiny_data.txt``` in your working directory.
