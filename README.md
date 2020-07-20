# Getting-and-Cleaning-Data
data science course final project

This is a repository for the final assignment of the Getting and Cleaning Data course of the JHU Data Science Specialization. 

In this project raw data from persons performing physical activities recorded with smartphone accelerometer and gyroscope were cleaned into a final dataset with an average for each variable for each subject and activity. 

The "final data.txt" file contains the final independent tidy dataset.

The "run_analysis.R" script is used to generate the final tidy dataset from the raw data files of test and train data.
The activity labels, subject labels and feature variables for each of the test and train data were first combined to generate data frames. The two data frames of test and train were merged into one. Mean and standard deviation related variables were extracted. Descriptive labels for activities were used to replace integer labels. Descriptive labels for column variable names were used to replace integer labels. Finally, the data were grouped by activity and the subjects, then an average is calculate for each variable, so that the final data set contains an average for each variable for each individual subject for each activity.

The "Project codebook.Rmd" file contains a codebook which provides a description and overview of the project as well as a description of the final tidy dataset variables. 
