<p align="center">
    <img src="./images/icons/python.PNG" alt="Python programming language logo." width="386" height="109">
    <img src="./images/icons/spark-logo-hd.png" alt="Flask icon." width="160" height="205">
</p>

# Stack Overflow Classifier

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Launch](#launch)
- [Screenshots](#screenshots)
- [Contributors](#contributors)

## Introduction
This is PySpark project which pre-processes and classifies answers to questions on Stack Overflow as having succesfully answered the question or not.

This PySpark application was created for a Big Data final group project for the course [SENG 550: Engineering Large Scale Analytics Systems](https://www.ucalgary.ca/pubs/calendar/current/software-engineering.html#43920).

The dataset used to train and test the application was posted by Chris Dubois of the University of California, Irvine, and can be found [here
](https://www.ics.uci.edu/~duboisc/stackoverflow/). 

## Features
- Pre-processes metadata of answer to questions on Stack Overflow.
- Classifies answers as succesfully answering a question based on if it is likely to have a community given score of at least 1.
- NumPy style documentation for maintainability and clarity of application.

## Launch
### Setup
To install necessary virtual environment, in a terminal enter:
```
pipenv install
```
To activate virtual environment needed to run application, in a terminal enter:
```
pipenv shell
```
To run application, in the opened shell, enter:
```
jupyter lab
```
This will open a jupyter lab tab in your default browser, in which you can run the application.

## Screenshots
### Training Data Evaluation Metrics for Each Classifier
<img src="images/results/training_data_eval_metrics.png" alt="A screenshot of the training data evaluation metrics for the different classifiers.">

### Validation Data Evaluation Metrics for Each Classifier
<img src="images/results/validation_data_eval_metrics.png" alt="A screenshot of the validation data evaluation metrics for the different classifiers.">

## Technologies
- [Python version 3.8.2](https://www.python.org/downloads/release/python-382/)
- [PySpark](https://spark.apache.org/docs/latest/api/python/index.html)
- [NumPy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)

## Contributors
<image x="74" y="74" width="64" height="64" style="border-radius: 5px" 
       src="https://avatars3.githubusercontent.com/u/51514472?s=460&u=0e68a59a1bed0101bf500753790048630779cc9b&v=4">
</image>
