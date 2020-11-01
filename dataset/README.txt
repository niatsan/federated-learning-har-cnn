The preprocessed data has 6 labels of activity. The activity set is listed as follows:
L1: Standing still (1 min) 
L2: Sitting and relaxing (1 min) 
L3: Lying down (1 min) 
L4: Walking (1 min) 
L5: Climbing stairs (1 min) 
L6: Running (1 min) 

NOTE: In brackets are the duration of the exercises (min).

The data collected for each subject is stored in a different log file: 'mHealth_subject<SUBJECT_ID>.csv'.
Each file contains the samples (by rows) recorded for all sensors (by columns).
The labels used to identify the activities are similar to the ones presented in Section 2 (e.g., the label for walking is '4'). In this preprocessed data, we do not use data from electrocardiogram signals.
The meaning of each column is detailed next:

Column 1: acceleration from the chest sensor (X axis)
Column 2: acceleration from the chest sensor (Y axis)
Column 3: acceleration from the chest sensor (Z axis)
Column 4: acceleration from the left-ankle sensor (X axis)
Column 5: acceleration from the left-ankle sensor (Y axis)
Column 6: acceleration from the left-ankle sensor (Z axis)
Column 7: gyro from the left-ankle sensor (X axis)
Column 8: gyro from the left-ankle sensor (Y axis)
Column 9: gyro from the left-ankle sensor (Z axis)
Column 10: magnetometer from the left-ankle sensor (X axis)
Column 11: magnetometer from the left-ankle sensor (Y axis)
Column 12: magnetometer from the left-ankle sensor (Z axis)
Column 13: acceleration from the right-lower-arm sensor (X axis)
Column 14: acceleration from the right-lower-arm sensor (Y axis)
Column 15: acceleration from the right-lower-arm sensor (Z axis)
Column 16: gyro from the right-lower-arm sensor (X axis)
Column 17: gyro from the right-lower-arm sensor (Y axis)
Column 18: gyro from the right-lower-arm sensor (Z axis)
Column 19: magnetometer from the right-lower-arm sensor (X axis)
Column 20: magnetometer from the right-lower-arm sensor (Y axis)
Column 21: magnetometer from the right-lower-arm sensor (Z axis)
Column 22: Label (0 for the null class)

*Units: Acceleration (m/s^2), gyroscope (deg/s), magnetic field (local)
