## Features

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

## Description of Variables

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

* tBodyAcc-XYZ
* tGravityAcc-XYZ
* tBodyAccJerk-XYZ
* tBodyGyro-XYZ
* tBodyGyroJerk-XYZ
* tBodyAccMag
* tGravityAccMag
* tBodyAccJerkMag
* tBodyGyroMag
* tBodyGyroJerkMag
* fBodyAcc-XYZ
* fBodyAccJerk-XYZ
* fBodyGyro-XYZ
* fBodyAccMag
* fBodyAccJerkMag
* fBodyGyroMag
* fBodyGyroJerkMag

The set of variables that were estimated from these signals are: 

* mean: Mean value
* std: Standard deviation


## Variables

 [1] "subject"                  "label"                    "tbodyaccmeanx"           
 [4] "tbodyaccmeany"            "tbodyaccmeanz"            "tbodyaccstdx"            
 [7] "tbodyaccstdy"             "tbodyaccstdz"             "tgravityaccmeanx"        
[10] "tgravityaccmeany"         "tgravityaccmeanz"         "tgravityaccstdx"         
[13] "tgravityaccstdy"          "tgravityaccstdz"          "tbodyaccjerkmeanx"       
[16] "tbodyaccjerkmeany"        "tbodyaccjerkmeanz"        "tbodyaccjerkstdx"        
[19] "tbodyaccjerkstdy"         "tbodyaccjerkstdz"         "tbodygyromeanx"          
[22] "tbodygyromeany"           "tbodygyromeanz"           "tbodygyrostdx"           
[25] "tbodygyrostdy"            "tbodygyrostdz"            "tbodygyrojerkmeanx"      
[28] "tbodygyrojerkmeany"       "tbodygyrojerkmeanz"       "tbodygyrojerkstdx"       
[31] "tbodygyrojerkstdy"        "tbodygyrojerkstdz"        "tbodyaccmagmean"         
[34] "tbodyaccmagstd"           "tgravityaccmagmean"       "tgravityaccmagstd"       
[37] "tbodyaccjerkmagmean"      "tbodyaccjerkmagstd"       "tbodygyromagmean"        
[40] "tbodygyromagstd"          "tbodygyrojerkmagmean"     "tbodygyrojerkmagstd"     
[43] "fbodyaccmeanx"            "fbodyaccmeany"            "fbodyaccmeanz"           
[46] "fbodyaccstdx"             "fbodyaccstdy"             "fbodyaccstdz"            
[49] "fbodyaccjerkmeanx"        "fbodyaccjerkmeany"        "fbodyaccjerkmeanz"       
[52] "fbodyaccjerkstdx"         "fbodyaccjerkstdy"         "fbodyaccjerkstdz"        
[55] "fbodygyromeanx"           "fbodygyromeany"           "fbodygyromeanz"          
[58] "fbodygyrostdx"            "fbodygyrostdy"            "fbodygyrostdz"           
[61] "fbodyaccmagmean"          "fbodyaccmagstd"           "fbodybodyaccjerkmagmean" 
[64] "fbodybodyaccjerkmagstd"   "fbodybodygyromagmean"     "fbodybodygyromagstd"     
[67] "fbodybodygyrojerkmagmean" "fbodybodygyrojerkmagstd" 

