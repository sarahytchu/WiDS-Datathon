WiDS Datathon 2020
===================================

The challenge is to create a model that uses data from the first 24 hours of intensive care to predict patient survival. MIT's GOSSIS community initiative has provided a dataset of more than 130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year time frame. This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States. 


## Data Descriptions


* **training_v2.csv** - The training data set with 91,713 encounters. Please view WiDS Datathon 2020 Dictionary.csv for the columns' definitions

* **unlabeled.csv** - The data set does not include hospital deaths variable. We are asked to predict it using the encounters in this file
* **WiDS Datathon 2020 Dictionary.csv** - supplemental information about the data

* **WiDS ICU** - Python file with EDA and Machine Learning models for predicting the ICU survival rate

## Project Workflow

* **Exploratory Data Analysis** 
  * Data Inspection (size of data, data types, percentage of missing values
  * Data Cleaning
  (1) Update column names
  (2) Filling missing 
  
 * Data Insights

## Models
Based on the data insights, we used **XGBoost algorithm** to make predictions for the following scenarios:
* **Model One**
* **Model Two**
* **Model Three**

