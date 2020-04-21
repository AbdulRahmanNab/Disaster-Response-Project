# Disaster-Response-Project
In the following projects we will be creating ETL and ML pipelines in order to classify text messages in a scenario where a disaster happended and we need to identify the class name of each text message and finally our model will be deployed in to a flask web application.

# Libraries
# import libraries
1. sys
2. sklearn
3. sqlalchemy
4. pandas
5. nltk
6. pickle
7. re

# Motivation and Summary
In a case where a disaster happens usually the organizations who are responsible for dealing with the consciences and providing help suffer from already limited capacity in helping everyone, so in order to maximize the operational excellence instead of wasting a lot of time, energy and capacity we are aiming to build a ETL and ML pipeline in order to preprocess the text data, load them into an SQL database, and then use it to train our Machine Learning Model using the an ML pipleline, and finally accessing the model from a Flask Web App.

# Files
├─ app<br>
│   ├─ templates<br>
│   └─ run.py<br>
├─ data<br>
│   ├─ InsertDatabaseName.db<br>
│   ├─ disaster_categories.csv<br>
│   ├─ disaster_messages.csv<br>
│   └─ process_data.py<br>
└─  models<br>
│   ├─ classifier.pkl<br>
│   └─ train_classifier.py<br>
