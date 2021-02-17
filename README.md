# Motion Recognition Dumbbell
Repository for my thesis project : Design and Realization of Motion Recognition Dumbbell Using Support Vector Machine Classifier On Embedded System

Abstract - Maintaining health by exercising can be done anywhere using simple tools such as dumbbells. The exercise that is done must be in accordance with the age and general health condition. If designed properly, weight-training programs for the elderly can improve strength, balance and joint stability. A system that can detect this movement is needed so that it can assist the user in using dumbbells.

In this thesis, a sports motion recognition dumbbell has been made. Dumbbell is equipped with an Innertial Measurement Unit (IMU) sensor, a single board computer Raspberry Pi Zero W and an RGB LED. Movement will be detected by the Innertial Measurement Unit (IMU) sensor and read the accelerometer and gyroscope values. Movement data is sent to the Raspberry Pi Zero W, which is then carried out with data preprocessing and modeling of the Support Vector Machine algorithm to obtain a sports motion recognition model for dumbbells. When motion is recognized, the Raspberry Pi Zero W will give the RGB LED command to turn on a certain color according to motion recognition.

The use of the Support Vector Machine method in processing data from the IMU sensor can detect the type of sports movement. Based on the results of trials conducted on 5 people with 6 movements detected, motion recognition dumbbells have a success rate of 90% -94%.

Keywords: dumbbell, motion recognition, Single Board Computer Raspberry Pi Zero W, Support Vector Machine
