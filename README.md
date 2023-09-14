# Predicting Taxi Driver given Trajectory for the Day

Yash Patel
Big Data Analytics, Worcester Polytechnic Institute, yppatel@wpi.edu


## 1 Introduction
With large data being collected, it is important to gain insight into the data to extract any features and make predictions with the data. We have a large dataset of paths that 5 taxi drivers used in one city for 6 months. The data included was the longitude and latitude of the driver at a certain time, the specific time, and whether the driver was currently driving someone around. Given this information, we would like to predict which driver (plate number) when given the trajectory of one taxi for the day.

## 2 Proposal
To achieve this prediction, I would like to train a neural network that when given a trajectory for the day would give the plate number of the driver. A trajectory is a list of data points. One data point contains the longitude, latitude, time, and status. The status is whether the driver was seeking for a passenger or currently serving a passenger. The goal is to extract overall performance for a trajectory and meaningful information from each data point

