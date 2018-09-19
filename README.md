# Unscented Kalman Filter Project 

In this project utilize an Unscented Kalman Filter to estimate the state of a moving object of interest with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower that the tolerance outlined in the project rubric. 


INPUT: values provided by the simulator to the c++ program

["sensor_measurement"] => the measurment that the simulator observed (either lidar or radar)


OUTPUT: values provided by the c++ program to the simulator

["estimate_x"] <= kalman filter estimated position x
["estimate_y"] <= kalman filter estimated position y
["rmse_x"]
["rmse_y"]
["rmse_vx"]
["rmse_vy"]

RUBIC POINTS :

Accuracy: The UKF accuracy was: 
Dataset 1 : RMSE <= [0.0630, 0.0836, 0.3196, 0.2158] 
Dataset 2 : RMSE <= [0.19, 0.6, 0.7, 0.2]
