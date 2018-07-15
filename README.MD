# Predict Daily Bike Rental

<img src="./udacity.PNG" alt="Udacity" width="250px"/>

Overview

---

My first neural network and understanding data distribution. 

**Project Goals**

The goals / steps of this project are the following:
* Use the simulator to collect data of good driving behavior
* Build, a convolution neural network in Keras that predicts steering angles from images
* Train and validate the model with a training and validation set
* Test that the model successfully drives around track one without leaving the road
* Summarize the results with a written report

**Project Files**

The repository consists of the following files: 
* model.py (script used to create and train the model)
* drive.py (script to drive the car)
* settings.py (script containing settings to run model.py)
* model.h5 (a trained Keras model with only center camera)
* model_all_camera.h5 (a trained Keras model with selective data and center, left and right camera)
* model_all_camera_all_data.h5 (a trained Keras model with all data and all camera angles)
* a README writeup file (either markdown or pdf)
* run1.mp4 and run2.mp4 (a video recording of your vehicle driving autonomously around the track for at least one full lap)

This README file describes how to output the video in the "Details About Files In This Directory" section.

[//]: # (Image References)

[image1]: ./Images/center_normal_0.jpg "Center Normal Road Image"
[image2]: ./Images/center_right_0_146.jpg "Right Turn Image"
[image3]: ./Images/center_left-0_217.jpg "Left Turn Image"
[image4]: ./Images/center_bridge_0.jpg "Bridge Road Image"
[image5]: ./Images/Loss_plot.png "Loss Plot Image"


**Dependencies**

The project requires the libraries desicribed in the environment.yml file. The environment can be setup using the file in anaconda. 

---

## Dataset

The dataset was created by me performing laps around the test track in the simluated environment. The simulator had two tracks avialbale to collect data. The data collection was divided as follows:
- Track1: Clockwise 4 laps
- Track1: Counterclockwise 2 laps
