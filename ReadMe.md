This is for Coursera final project for getting and cleaning data.

The R script called run_analysis.R does the following. 

Download the dataset if it does not already exist in the working directory.The dataset contains test set and train set.

Loads train/X_train.txt which contains all the meseaurements for training set.

Assigns the variable names to the training dataset from features.txt

Loads the subjects from train/subject_train.txt and assigns these to training set

Loads activity Id for each measurement of train dataset from train/y_train.txt

Loads test/X_test.txt which contains all the test meseaurements.

Assigns the variable names to the test dataset from features.txt

Loads the subjects to the test dataset from test/subject_test.txt

Loads activity Id for each measurement of test dataset from test/y_test.txt

Merge the training and the test set to create one data set.

Extracts only the measurements on the mean and standard deviation for each measurement from the merged dataset.It looks for std() and mean().

Assigns descriptive activity name to name the activities in the merged data set

Creates final dataset with average of each variable for each activity and each subject.

The final reasult is tidydata.txt which consistis of subject,activityname and average of measurements for each subject and activity