The code book that describes the variables, the data, and any transformations or work in the project.
The run_analysis.R scripts explain how all of the scripts work and how they are connected, including:
1.Merges the training and the test sets to create one data set. 2.Extracts only the measurements on the mean and standard deviation for each measurement. 3.Uses descriptive activity names to name the activities in the data set 4.Appropriately labels the data set with descriptive variable names. 5.From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. 6.In this project, TidyData.txt is output.

Review criterialess
#1 The submitted data set is tidy. #2 The Github repo contains the required scripts. #3 GitHub contains a code book that modifies and updates the available codebooks with the data to indicate all the variables and
summaries calculated, along with units, and any other relevant information. #4 The README that explains the analysis files is clear and understandable. #5 The work submitted for this project is the work of the student who submitted it.

Data Set Information:
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.

Attribute Information:
For each record in the dataset it is provided:

Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
Triaxial Angular velocity from the gyroscope.
A 561-feature vector with time and frequency domain variables.
Its activity label.
An identifier of the subject who carried out the experiment.
Description of abbreviations of measurements
leading t or f is based on time or frequency measurements.
Body = related to body movement.
Gravity = acceleration of gravity
Acc = accelerometer measurement
Gyro = gyroscopic measurements
Jerk = sudden movement acceleration
Mag = magnitude of movement
mean and SD are calculated for each subject for each activity for each mean and SD measurements.
The units given are g’s for the accelerometer and rad/sec for the gyro and g/sec and rad/sec/sec for the corresponding jerks.
