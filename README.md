# Assignment1
# Human Activity Recognition Data Analysis

## Introduction

This repository contains an analysis of the "Human Activity Recognition Using Smartphones" dataset. The data was collected from a group of 30 volunteers performing six activities (e.g., WALKING, STANDING, LAYING) while wearing a Samsung Galaxy S II smartphone. The dataset includes sensor data from accelerometers and gyroscopes and provides information on various body movements.

The goal of the analysis is to demonstrate the ability to collect, clean, and manipulate data for later use in analysis. Specifically, we will combine training and test data, extract relevant features, and generate a tidy dataset that provides insights into the relationship between physical activity and sensor measurements.

The dataset and project were inspired by the work of Anguita et al. (2012) in the field of human activity recognition.

## Objectives

The primary objective of this analysis is to prepare a tidy dataset that can be used for further analysis or modeling. The steps performed include:

1. Merging the training and test data sets.
2. Extracting measurements on the mean and standard deviation for each measurement.
3. Using descriptive activity names to name the activities.
4. Appropriately labeling the data set with descriptive variable names.
5. Creating a second tidy data set that contains the average of each variable for each activity and each subject.

## Script: `run_analysis.R`

The `run_analysis.R` script performs the following steps:

1. **Data Merging**: Combines the training and test data into one dataset.
2. **Feature Selection**: Extracts measurements on the mean and standard deviation.
3. **Activity Labeling**: Labels the activities with descriptive names.
4. **Variable Labeling**: Assigns descriptive variable names to the data.
5. **Data Aggregation**: Creates a tidy dataset with the average of each variable for each activity and each subject.

### Required Libraries

The script requires the `dplyr` library for data manipulation. You can install it by running:

```R
install.packages("dplyr")

Running the Script:
1.) Download the dataset from the following link: Human Activity Recognition Dataset.
2.) Unzip the dataset and place it in your working directory.
3.) Download and run the run_analysis.R script.
4.) The script will generate a tidy data set, saved as tidy_data.txt.

### Expected Output:
The final output is a tidy data set that contains the average of each variable for each subject and activity. This tidy dataset will be saved as tidy_data.txt in the working directory. The dataset contains the following columns:
Subject: The identifier of the subject who performed the activity.
Activity: The activity label (e.g., WALKING, STANDING).
Columns corresponding to the mean and standard deviation measurements for each feature.


