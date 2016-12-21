# Getting-and-cleaning-data-course-project
* Match descriptive activity names to activity value in data set.
* Merge training and test data sets to be one data set (HAR_data_all value)
* extract only mean and sd for each measurement by using grep function with regular expression to extract column names which contain      "mean" and "std" string.
* Change labels to appropriate labels and use make.names function to make suitable name.
* Use package dplyr to group and calculate the average of each variables for each activity and each subject.
