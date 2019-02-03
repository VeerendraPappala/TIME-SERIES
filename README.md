# TIME-SERIES
The time series data most of us are exposed to deals primarily with generating forecasts. Whether that’s predicting the demand or sales of a product, the count of passengers in an airline or the closing price of a particular stock,
As you can imagine, time series classification data differs from a regular classification problem since the attributes have an ordered sequence

## Problem Statement
We will be working on the **‘Indoor User Movement Prediction‘**  problem. In this challenge, multiple motion sensors are placed in different rooms and the goal is to identify whether an individual has moved across rooms, based on the frequency data captured from these motion sensors.

There are four motion sensors (A1, A2, A3, A4) placed across two rooms. Have a look at the below image which illustrates where the sensors are positioned in each room. The setup in these two rooms was created in 3 different pairs of rooms (group1, group2, group3).

A person can move along any of the six pre-defined paths shown in the above image. If a person walks on path 2, 3, 4 or 6, he moves within the room. On the other hand, if a person follows path 1 or path 5, we can say that the person has moved between the rooms.

The sensor reading can be used to identify the position of a person at a given point in time. As the person moves in the room or across rooms, the reading in the sensor changes. This change can be used to identify the path of the person.

## Reading and Understanding the Data

Our dataset comprises of 316 files:

* 314 MovementAAL csv files containing the readings from motion sensors placed in the environment
* A Target csv file that contains the target variable for each MovementAAL file
* One Group Data csv file to identify which MovementAAL file belongs to which setup group
* The Path csv file that contains the path which the object took

## The project is broken down into multiple steps:

* Load and preprocess the  dataset
* Train the  classifier on your dataset
* Use the trained classifier to predict test data 
* picking up the best model

The model is built on **KERAS**

 
## Installing Keras
 conda install keras
 
 To know much about keras, check my repo on [KERAS](https://github.com/VeerendraPappala/KERAS)
 
 

### Everything you need to recreate this project is on the jupyter notebook. Everything was coded in Google Colab, because of its GPU. I uploaded the dataset to Google Drive, so you can download it directly (the code to download it is in the notebook). 

