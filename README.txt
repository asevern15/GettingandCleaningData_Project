Course Project:

You should create one R script called run_analysis.R that does the following.

1.Merges the training and the test sets to create one data set.
2.Extracts only the measurements on the mean and standard deviation for each measurement.
3.Uses descriptive activity names to name the activities in the data set
4.Appropriately labels the data set with descriptive activity names.
5.Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Steps to use run_analysis:

1.Download the data source.
2.setwd() to the folder of the data.
3.Code uses reshape2 and data.table, so make sure those are installed.
4.Run run_analysis.R, it will generate a new file tiny_data.txt in your working directory.
