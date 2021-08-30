# Project 5 Data Science Capstone Project
Repository for Project Number 5 in the Udacity Data Science Course

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [Sourced Data](#data)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The following libraries are required from pypsark:
* pyspark.sql
* pyspark.sql.functions 
* pyspark.sql.types
* pyspark.ml

There should be no other necessary libraries to run the code here beyond the Anaconda distribution of Python; with
* numpy
* pandas
* datetime
* matplotlib.pyplot
* %matplotlib inline 
* seaborn
* collections
being used

The code should run with no issues using Python versions 3.*.

## Project Motivation<a name="motivation"></a>

Customer facing businesses are continually faced with the chellenge of predicting so called _churn_ rates, that is to say the rate at which businesses lose customers through cancellation of subscriptions or contracts.
The motivation of this project is to develop a machine learning model to predict if customers will churn.
Using Spark, it is possible to work efficiently with large datasets in order to produce such models, and the project sets out to study a customer dataset, manipulate and prepare it for machine learning, and then identify effective machine learning models for predicting _churn_ rates using this prepared data.
If accurate such predictions are incredibly valuable, in helping businesses retain customers and protect revenues.

## Sourced Data <a name="data"></a>

* This project will be using customer data from the fictional online music streaming platform **_Sparkify_**
* The dataset contains records of all the interactions each **_Sparkify_** user has with the platform together with an associated timestamp, be it playing songs, giving thumbs ups, adding playlists or just logging in and out. It also contains the all important record of the all important cancellation event; the so called _churn_.
* For the project workbook a subset of the main data set was provided, which has been downloaded and saved as 'mini_sparkify_event_data.json'.
* The full dataset can be found [here](s3n://udacity-dsnd/sparkify/sparkify_event_data.json)

## File Descriptions <a name="files"></a>

#### 1. `README.md`

This readme file.

#### 2. `sparkify.ipynb` 

This is the Jupyter note book that showcases the data preparation, analysis and machine-learning process for this project. It contains 
* pyspark scripts for 
   - loading the data set
   - exploring the data set
   - cleaning the data set
* pandas and seaborn transforms for providing 
   - exploratory data analysis 
   - visualisations
* pyspark scripts for 
   - aggregating the data, 
   - creating machine learning pipelines,
   - running predictions,
   - assessing predictions,
   - tuning machine learning models
* comprehensive markdown commentary explaining the steps and giving insights to the results.

## Results<a name="results"></a>

The main findings of the code can be found at the post [here](https://richard-needham.medium.com/predicting-churn-rates-for-sparkify-45bed481f34).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Udacity for the dataset and screenshot image of the **_Sparkify_** logo and Insight Data Science

Insight Data Science for the extra-curricular material on Spark programming
Insight Data Science is a fellowship program for aspiring data scientists, data engineers, and data product managers. You can read more about their fellowship programs on their website www.insightdatascience.com.

Definitions for Precision and recall wer pbtained from [wikipedia](https://en.wikipedia.org/wiki/Precision_and_recall)

The code is supplied as is, feel free to use the code here as you would like! 
