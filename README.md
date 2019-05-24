# Sparkify-project
### Building Customer Churn Predictive Model Using SPARK

This repository contains the results of the Data Science Nanodegree Sparkify Capstone Project. Its’s purpose is to give the reviewers access to the code. More information can be found on a [Medium Blog Post](https://medium.com/@vanamsrikanth/customer-churn-prediction-for-music-app-using-pyspark-4127c3c00c1f).


## Table of Contents
  - Installation
  - Project Motivation
  - Files Description
  - Result
  - Licensing, Authors, and Acknowledgements
  
  
## Installation
  
    This project uses the following software and Python libraries:

    Python
    Spark
    Pyspark
    pandas
    Matplotlib
    Seaborn

You will also need to have software installed like Anaconda to run and execute a Jupyter Notebook.

## Project Motivation

#### developing Skills of:

- Loading large datasets into Spark and manipulating them using Spark SQL and Spark Dataframes
- Using the machine learning APIs within Spark ML to build and tune models
- Integrating the skills I've learned in the Spark course and the Data Scientist Nanodegree program

## Files Description

- Sparkify.ipynb Notebook is main file of the project.
- It demonstrates the process of using pyspark to explore the data and build the model.

## Result
We Split the feature & target variable data set into train, test and then built pipeline and implemented 3 machine learning models.
Since the churned users are a fairly small subset, we used F1 score as the metric to optimize and we found GBTClassifier better model compared to other One.

I post a blog about the detail, you can find it [here](https://medium.com/@vanamsrikanth/customer-churn-prediction-for-music-app-using-pyspark-4127c3c00c1f).

## Licensing, Authors, Acknowledgements

Must give credit to Udacity for the project. And  instructions in the notebook are also well prepared by Udacity team.

