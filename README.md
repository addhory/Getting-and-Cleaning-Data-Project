# Getting and Cleaning Data Project

## Goal of the Project
1. A tidy data set 
2. A link to a Github repository with your script for performing the analysis 
3. A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
4. Analysis R Script

### Description
This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

    1. Download the dataset if it does not already exist in the working directory
    2. Load the activity and feature info
    3. Loads both the training and test datasets, keeping only those columns which
    reflect a mean or standard deviation
    4. Loads the activity and subject data for each dataset, and merges those
    columns with the dataset
    5. Merges the two datasets
    6. Converts the `activity` and `subject` columns into factors
    7. Creates a tidy dataset that consists of the average (mean) value of each
    variable for each subject and activity pair.
   
The end result is shown in the file `tidy.txt`.

### Source Data
Data + Description can be found here [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

### Data Set Information
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

## Review Criteria

Goal | Item | Link to Item
--- | --- | ---
Analysis R Script |  run_analysis.R |  [R Script Link](https://github.com/RidhoAnshory/Getting-and-Cleaning-Data-Project/blob/master/run_analysis.R "run_analysis.R")
Tidy Data Set |  Clean Data Set |  [Data Set Link](https://github.com/RidhoAnshory/Getting-and-Cleaning-Data-Project/blob/master/data/tidyData.txt "tidyData.txt")
Codebook | CodeBook.md |  [Repo Link](https://github.com/RidhoAnshory/Getting-and-Cleaning-Data-Project/blob/master/CodeBook.md "CodeBook.md")



