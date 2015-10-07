# Getting and cleaning data

## Files
* README.md 
* CodeBook.md 
* run_analysis.R 

## Tasks

One of the most exciting areas in all of data science right now is wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

 You should create one R script called run_analysis.R that does the following.
 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps

1. Reads training and the test sets. Merges the training ('train_***') and the test ('test_***') sets to create one data set ('data').
2. Reads from 'features.txt' and extracts only the measurements on the mean ("mean") and standard deviation ("std") for each measurement into data set called 'features_mean_std'. Extracts only relevant columns from data set 'data' into data set 'data_mean_std'.
3. Reads from 'activity_labels.txt' and uses descriptive activity names to name the activities in the data set 'data_mean_std'.
4. Extracts column names from data set 'features_mean_std' into data set 'good_colnames'.  Appropriately labels the data set with descriptive variable names into data set 'data_mean_std'. 
5. From the data set in step 4, creates a second, independent tidy data set called 'aggr_data' with the average of each variable for each activity and each subject. Exports the data from 'aggr_data' into a text file called 'tidy.txt'.
