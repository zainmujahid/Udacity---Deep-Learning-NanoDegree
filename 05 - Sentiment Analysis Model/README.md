# Deployin a Sentiment Analysis Model

## Project Overview
In this project I constructed a Recurrent Neural Network for the purpose of determining the sentiment of a movie review using the IMDB data set. I created this model using Amazon's SageMaker service. In addition, I deployed the model and constructed a simple web app which interacts with the deployed model.

## Purpose
The goal of this project was to deploy a RNN based model over AWS SageMaker using public API Gateway.

## Working
The web app takes the user-provided review and predicts if the entered review was POSITIVE or NEGATIVE. The working of the project is shown below: 
![](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/05%20-%20Sentiment%20Analysis%20Model/resources/working.gif)

## Results
Following are 2 results of this project:
- POSITIVE <br>
![](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/05%20-%20Sentiment%20Analysis%20Model/resources/positive.PNG)
- NEGATIVE <br>
![](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/blob/master/05%20-%20Sentiment%20Analysis%20Model/resources/negative.PNG)

## Notes
I'm letting the endpoint to run for sometime so you guys can try this project out but I can not let it to run infinitely. To implement this project for yourself you will need to create your own endpoint and generate the API URL and replace it in the ```/website/index.html``` <br>

To view the full project files click [here](https://github.com/zainmujahid/Udacity---Deep-Learning-NanoDegree/tree/master/05%20-%20Sentiment%20Analysis%20Model)
