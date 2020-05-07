# TV Script Generator
This folder contains my solution to the _"TV Script Generation"_ problem presented as the third project in the Deep Learning Nano Degree by Udacity.

### Overview
For this project I was given a 3.41 MB file of Scripts taken from the Seinfeld sitcom.

### Purpose and Results
Before training the model, the dataset must be prepared by removing tokens and identifying unique words. With batches and sequence lengths specified, dataloaders can be created.

![](images/Dataset.png)

The Goal of the project is to train a Recurrent Neural Network on the scripts and use the trained model to generate new scripts.

![](images/Results.png)

This Model achieved a training loss of 3.43, with the following hyperparameters:
* <b>sequence_length</b>: This value was tested at 200, then 100, then 50, then 25, then 10. 
* <b>batch_size</b>: this value was set to 50, then 100 then 200. 
* <b>num_epochs</b>: this value was statically set to 20. 
* <b>learning_rate</b>: this value was tested at 0.01, then 0.001. 
* <b>embedding_dim</b>: This value was tested at 300, then 400 and 200. 
* <b>hidden_dim</b>: This value was tested at 256, then 512 and 128. 
* <b>n_layers</b>: this value was statically set to 2. 