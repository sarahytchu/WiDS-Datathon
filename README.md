WiDS Datathon 2020
===================================

The challenge is to create a model that uses data from the first 24 hours of intensive care to predict patient survival. MIT's GOSSIS community initiative has provided a dataset of more than 130,000 hospital Intensive Care Unit (ICU) visits from patients, spanning a one-year time frame. This data is part of a growing global effort and consortium spanning Argentina, Australia, New Zealand, Sri Lanka, Brazil, and more than 200 hospitals in the United States. 


## Data Descriptions


* **training_v2.csv** - The training data set with 91,713 encounters. Please view WiDS Datathon 2020 Dictionary.csv for the columns' definitions

* **unlabeled.csv** - The data set has 39,308 encounters, does not include hospital deaths variable, and is used to predict hospital death

* **WiDS Datathon 2020 Dictionary.csv** - supplemental information about the data

The above three files can be accessed [here](https://www.kaggle.com/c/widsdatathon2020/data).

* **ICU Survival Analysis** - Python file with full analysis and prediction utilizing the XGBoost Model
