# Predicting Bike Sharing Patterns

## Overview
For this project I was given a dataset of bike sharing patterns, which can be found <a href="https://www.capitalbikeshare.com/system-data">here</a>. This data included the following attributes: 

* Duration – Duration of trip
* Start Date – Includes start date and time
* End Date – Includes end date and time
* Start Station – Includes starting station name and number
* End Station – Includes ending station name and number
* Bike Number – Includes ID number of bike used for the trip
* Member Type – Indicates whether user was a "registered" member or a "casual" rider

## Purpose
The goal of this project was to create a prediction model that took in the above attributes as inputs and predicted the number of bikes hired as an output.

![](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/01%20-%20Predicting%20Bike-Sharing%20Patterns/Images/neural_network.png)

## Methadology
1. First, I read the dataset into memory. Then I extracted the relevent fields and scaled the inputs against a mean and standard deviation found in the dataset. 

2. Next, I implemented the solution for creating a Neural Network in python. All code for the implementation can be found <a href="https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/01%20-%20Predicting%20Bike-Sharing%20Patterns/Your_first_neural_network/my_answers.py">here</a>. 

3. Lastly, the Neural Network is initialized and trained. Its performance for training and validation loss can be seen in the image below.

![](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/01%20-%20Predicting%20Bike-Sharing%20Patterns/Images/loss.png)

## Results
Finally, the Neural Network is run against unseen testing data with its accuracy shown in the image below.

![](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/01%20-%20Predicting%20Bike-Sharing%20Patterns/Images/test.png)

## Conclusion
This project introduced me to the concepts of what a neural network is (all maths included) and what a neural network can do. It gave a practical real world example and a solution that utilizes deep learning. I thoroughly enjoyed it as my introduction into the deep learning nano degree.
<br><br>
To view the full project [click here](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/01%20-%20Predicting%20Bike-Sharing%20Patterns/Your_first_neural_network/Your_first_neural_network.ipynb)