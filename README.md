WiDS Datathon 2020
===================================

The challenge is to create a model that uses data from the first 24 hours of intensive care to predict patient survival. MIT's GOSSIS community initiative has provided a dataset of more than 130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year time frame. This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States. 


## Data Descriptions


* **training_v2.csv** - The training data set with 91,713 encounters. Please view WiDS Datathon 2020 Dictionary.csv for the columns' definitions

* **unlabeled.csv** - The data set has 39,308 encounters, does not include hospital deaths variable, and is used to predict hospital death

* **WiDS Datathon 2020 Dictionary.csv** - supplemental information about the data

* **WiDS ICU** - Python file with EDA and Machine Learning models for predicting the ICU survival rate

## Project Workflow

* **Exploratory Data Analysis** 
  * Data Inspection (data size, data types, percentage of missing values)
  * Data Cleaning
  (1) Update column names
  (2) Fill in missing values 
  * Data Profile
* **Data Modeling** - Based on the data insights, we used **XGBoost algorithm** to predict the following scenarios:
  * *[Name of the First Scenario]*
  * *[Name of the Second Scenario]*
  * *[Name of the Third Scenario]*

Profile
Display academic project and personal portfolio
</br>
</br>
</br>
</br>
</br>
<h1>Personal Project Outline</h1>
- [Wids Datathon 2020 | Predict ICU death probability](#wids_datathon_2020)
- [Babson Analytics Hackathon 2020 | Merchandising Analytics Case Study](#babson_hackathon_2020)
</br>
</br>
</br>
---
<h2 id="wids_datathon_2020">Wids Datathon 2020 | Predict ICU death probability</h2>
<h3>Notebook:</h3>
- [Predict encounter death probability using XGBoost](https://github.com/chen-szuyu-cody/portfolio/blob/master/Project/wids_datathon_2020/Predict%20encounter%20death%20probability%20using%20XGBoost.ipynb)
<h3>Overview</h3>
The challenge is to create a model that uses data from the first 24 hours of intensive care to predict patient survival. MIT's GOSSIS community initiative, with privacy certification from the Harvard Privacy Lab, has provided a dataset of more than 130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year timeframe. This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States.
Labeled training data are provided for model development; you will then upload your predictions for unlabeled data to Kaggle and these predictions will be used to determine the public leaderboard rankings, as well as the final winners of the competition.
<h3>Data Description</h3>
