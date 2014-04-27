GettingandCleaningData-Project
==============================

* Unzip the source
  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
  into a folder, eg C:\Users\DELL\Desktop\CleaningDataProject\

* Put run_analysis.R to C:\Users\DELL\Desktop\CleaningDataProject\UCI HAR Dataset\

* The folowing R script, it will read the dataset and generate these files:
  1) merged_clean_data.txt  -- 8.35 Mb, a 10299x68 data frame
  2) data_set_with_the_averages.txt  -- 0.225 Mb, a 180x68 data frame

  in RStudio run:
  
  setwd("C:\\\\Users\\\\DELL\\\\Desktop\\\\CleaningDataProject\\\\UCI HAR Dataset\\\\")
  
  source("run_analysis.R")
