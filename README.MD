# Predict Daily Bike Rental

<img src="./udacity.PNG" alt="Udacity" width="250px"/>

Overview

---

My first neural network and understanding data distribution. 

**Project Goals**

The goals / steps of this project are the following:
* Predict daily bike rental ridership
* Build your first neural network
* Train and validate the model with a training and validation set
* Test that the model
* Summarize the results with a written report

**Project Files**

The repository consists of the following files: 
* Predicting_bike_sharing_data.ipynb (Main python notebook to create and train the model)
* Predicting_bike_sharing_data.pdf (HTML version of main notebook)
* day.csv (Dataset file)
* hour.csv (Dataset file)


[//]: # (Image References)

[image1]: ./assets/data.png "Explore Data"
[image2]: ./assets/learning.png "Learning"
[image3]: ./assets/neural_network.png "Model"
[image4]: ./assets/results.png "Results"


**Dependencies**

The project requires the libraries desicribed in the environment.yml file. The environment can be setup using the file in anaconda. 

---

## Dataset

The data comes from the UCI Machine Learning Database. Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. 

- day.csv
- hour.csv

data_path = 'Bike-Sharing-Dataset/hour.csv'

![image1]

## Model Selection

![image3]

| Parameter | Value |
| --- | ----------- |
| iterations | 5000 |
| learning_rate | 0.5 |
| hidden_nodes | 25 |
| output_nodes | 1 |

## Training

![image2]

## Results

![image4]
