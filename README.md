# Disaster Response Pipelines

## 📝Table of Contents 
* Project Description
* Installation
* File Descriptions
* Licensing, Authors, Acknowledgements


## 📝Project Description
This project seeks to build a model that can classify messages sent during a disaster situation (earthquakes, hurricanes, floods, etc.) into predetermined categories. This classification allows aid agencies to receive messages in a timely manner and according to their specialty.

To carry out this project, you must build a basic ETL pipeline that loads and cleanses the data, and is ready to model and analyze it. An ML model is included to categorize new received messages.

## 🔌Installation
Developed with Python 3 with libraries of:
  * numpy 
  * pandas 
  * sqlalchemy
  * re
  * nltk
  * pickle 
  * sklearn
  * warnings

## 📁File Descriptions
  * disaster_categories.csv: Database containing the ID, the message that was sent, and the gender
  * disaster_messages.csv: Database containing the ID and the categories the message belonged to
  * DisasterResponse.db: Cleaned data
  * process_data.py: Code used for cleaning and preprocessing data.
  * train_classifier.py: Code used to train the model
  * classifier.pkl: Trained model
  * run.py: To run Web App

## 📚Licensing, Authors, Acknowledgements
This application was made as part of the [Udacity Data Scientist Nanodegree](https://learn.udacity.com/my-programs?tab=Currently%2520Learning) program, who provided the code templates and data. The original data was provided by [Figure Eight's](https://appen.com/#customers) Udacity.
