# Unscented Kalman Filter

This is a project to implement Unscented Kalman filter to track objects. This Project is the seventh task (Project 2 of Term 2) of the Udacity Self-Driving Car Nanodegree program. 
The main goal of the project is to apply Unscented Kalman Filter to fuse data from LIDAR and RADAR sensors of a self driving car using C++.


The project was created with the Udacity Starter Code and snippets from Unscented Kalman Filter lessons.

## Contents of this repo:
* **src:**    Contains all the source files. Files modified as part of implementation are *ukf.cpp*, *ukf.h* and *tools.cpp*
* **build:**  Contains all the files generated as part of the build including unscentedKF executable.
* **result:** Folder contains image files having NIS graphs plotted for Radar and Laser
* **CMakelists.txt

Other files contents are not modified.

The project uses measurement data from Laser and Radar sensors from the simulator to estimate the position of the object. 
The resulting RMSE values are within the threshold requirements of the project.

## Output values of project run on Dataset 1
### RMSE:
**px:** 0.0686     
**py:** 0.0815
**vx:** 0.2846 
**vy:** 0.1938
