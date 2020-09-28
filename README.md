# GettingAndCleaningData

This project for the final course project in the coursera course: Getting and Cleaning Data by JHU.


The included R script, run_analysis.R, conducts the following: 
Download the dataset from web if it does not already exist in the working directory. 
Read both the train and test datasets and merge them into x(measurements), y(activity) and subject, respectively. 
Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). 

Then change the column names to be descriptive. 

Extract data by selected columns, and merge x, y(activity) and subject data. 
Finally, replace y(activity) column to it's name by refering activity label. 

Generate 'Tidy Dataset' that consists of the average (mean) of each variable for each subject and each activity. 

The result is shown in tidy_dataset.txt also csv version is included to be viewed on GitHub.
