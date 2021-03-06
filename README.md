
## Introduction

Flask is a micro web framework written in Python. It is classified as a microframework because it does not require particular tools or libraries
## Prerequisites

You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.
## Project Structure

This project has four major parts :

1. model.py - This contains code fot our Machine Learning model to predict employee salaries absed on trainign data in 'hiring.csv' file.

2. app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.

3. request.py - This uses requests module to call APIs already defined in app.py and dispalys the returned value.

4. templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.


## Running the project

1. Ensure that you are in the project home directory. Create the machine learning model by running below command


python model.py


This would create a serialized version of our model into a file model.pkl

2. Run app.py using below command to start Flask API


python app.py


If everything goes well, you should be able to see the predcited salary vaule on the HTML page!


3. You can also send direct POST requests to FLask API using Python's inbuilt request module Run the below command to send the request with some pre-popuated values 


python request.py


## Conclusion

In this project we learned to deploy simple flask deployment project


![1](https://user-images.githubusercontent.com/99526815/166093343-f37d0dd4-047f-4b6a-a8b6-1d4db7997694.PNG)

![2](https://user-images.githubusercontent.com/99526815/166093350-db508df0-b40f-41fb-bc2c-33428fd10aaa.PNG)
