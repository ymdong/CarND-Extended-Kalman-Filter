# Extended Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

In this project, a kalman filter is constructed using C++ to estimate the state of a moving object based on the senor fusion of noisy lidar and radar measurements. For lidar data, the standard kalman filter is used, but for radar data, an extended kalman filter is used due to the nonlinearity of measurement function.

As shown in the figure below, the obtained RMSE values for estimated position and velocity are lower than the tolerance outlined in the project rubric. The red and blue dot are the lidar and radar data point and the green dot is the estimated position of the object.

[//]: # (Image References)

[image1]: ./img1.png "Estimated trajectory using kalman filter"

![alt text][image1]



