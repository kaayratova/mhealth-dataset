# mhealth-dataset
Dataset for ds552 course project

Dataset is taken from https://archive.ics.uci.edu/dataset/319/mhealth+dataset 

The MHEALTH (Mobile HEALTH) dataset comprises body motion and vital signs recordings for ten volunteers of diverse profile while performing several physical activities. Sensors placed on the subject's chest, right wrist and left ankle are used to measure the motion experienced by diverse body parts, namely, acceleration, rate of turn and magnetic field orientation. The sensor positioned on the chest also provides 2-lead ECG measurements, which can be potentially used for basic heart monitoring, checking for various arrhythmias or looking at the effects of exercise on the ECG.

DATASET SUMMARY:  
#Activities: 12   
#Sensor devices: 3  
#Subjects: 10  

ACTIVITY SET (CLASSES)
The activity set is listed in the following:  
L1: Standing still (1 min)   
L2: Sitting and relaxing (1 min)   
L3: Lying down (1 min)   
L4: Walking (1 min)   
L5: Climbing stairs (1 min)   
L6: Waist bends forward (20x)   
L7: Frontal elevation of arms (20x)  
L8: Knees bending (crouching) (20x)  
L9: Cycling (1 min)  
L10: Jogging (1 min)  
L11: Running (1 min)  
L12: Jump front & back (20x)  
NOTE: In brackets are the number of repetitions (Nx) or the duration of the exercises (min).  

FEATURES  
Column 1: acceleration from the chest sensor (X axis)  
Column 2: acceleration from the chest sensor (Y axis)  
Column 3: acceleration from the chest sensor (Z axis)  
Column 4: electrocardiogram signal (lead 1)  
Column 5: electrocardiogram signal (lead 2)  
Column 6: acceleration from the left-ankle sensor (X axis)  
Column 7: acceleration from the left-ankle sensor (Y axis)  
Column 8: acceleration from the left-ankle sensor (Z axis)  
Column 9: gyro from the left-ankle sensor (X axis)  
Column 10: gyro from the left-ankle sensor (Y axis)  
Column 11: gyro from the left-ankle sensor (Z axis)  
Column 13: magnetometer from the left-ankle sensor (X axis)  
Column 13: magnetometer from the left-ankle sensor (Y axis)  
Column 14: magnetometer from the left-ankle sensor (Z axis)  
Column 15: acceleration from the right-lower-arm sensor (X axis)  
Column 16: acceleration from the right-lower-arm sensor (Y axis)  
Column 17: acceleration from the right-lower-arm sensor (Z axis)  
Column 18: gyro from the right-lower-arm sensor (X axis)  
Column 19: gyro from the right-lower-arm sensor (Y axis)  
Column 20: gyro from the right-lower-arm sensor (Z axis)  
Column 21: magnetometer from the right-lower-arm sensor (X axis)  
Column 22: magnetometer from the right-lower-arm sensor (Y axis)  
Column 23: magnetometer from the right-lower-arm sensor (Z axis)  
Column 24: Label (0 for the null class)  

*Units: Acceleration (m/s^2), gyroscope (deg/s), magnetic field (local), ecg (mV)

REFERENCE:  
Banos, O., Garcia, R., Holgado-Terriza, J.A., Damas, M., Pomares, H., Rojas, I., Saez, A., Villalonga, C.: 
mHealthDroid: a novel framework for agile development of mobile health applications. 
In: Proceedings of the 6th International Work-conference on Ambient Assisted Living an Active Ageing (IWAAL 2014), Belfast, United Kingdom, December 2-5 (2014)
