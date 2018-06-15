# Getting and Cleaning Data Project
Author: Raveendra Swarna <br />
Blog Post: 
Data Zip File Location: [UC Irvine Repo](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip "Clicking will download the data")

## Goal of the Project
1. A tidy data set 
2. A link to a Github repository with your script for performing the analysis 
3. A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
4. Analysis R Script

## Review Criteria

Goal | Item | Link to Item
--- | --- | ---
Analysis R Script |  run_analysis.R |  [R Script Link](https://github.com/swarnaravi/GettingCleaningDataCourseProject/run_analysis.R "run_analysis.R")
Tidy Data Set |  Clean Data Set |  [Data Set Link](https://github.com/swarnaravi/GettingCleaningDataCourseProject/blob/master/data/tidyData.txt "tidyData.txt")
Github Repo | Repo |  [Repo Link](https://github.com/swarnaravi/GettingCleaningDataCourseProject/tree/master/ "Click to go to Repo")
README | ReadingItNow |  [Repo Link](https://github.com/swarnaravi/GettingCleaningDataCourseProject/README.md "README.md")

The dataset includes the following files:
=========================================
Tidy dataset:

- 'tidydata.txt': Tidy dataset containing the average of each mean() and std() variable for each activity and each subject

- 'run_analysis.R': code for creating the tidy dataset

- CodeBook.md: document describing the variables, data, and transformations performed to clean up the data

- 'README.md'

Files needed to run 'run_analysis.R':
=========================================
- 'train/X_train.txt': Training set.

- 'train/y_train.txt': Training labels.

- 'test/X_test.txt': Test set.

- 'test/y_test.txt': Test labels.

- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30. 

- 'test/subject_test.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 24. 

## Contributors

FirstName | LastName | Email
--- | --- | ---
Raveendra |  Swarna |  <swarnaravistar@gmail.com>

## License

Anyone may contribute after this assignment is turned in and graded. 

## Blog Posts on the Specialization | John Hopkins Coursera

Notes: 
======
- Features are normalized and bounded within [-1,1].
- Each feature vector is a row on the text file.
