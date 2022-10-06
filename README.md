# Disaster-Response-Pipeline
# Installation
All libraries are avilable in Jupyter notebook distribution of Python. Following libraries have been used:

pandas
re
sys
json
sklearn
nltk
sqlalchemy
pickle
Flask
plotly
sqlite3

# Description

This project is the second project of Data Scientist Nanodegree on Udacity using Disaster-Response-Pipeline Open Data by following the Rubric process; therefore, three steps have been implemented to analyse the data:

1- Project Workspace - ETL

Loads the messages and categories datasets

Merges the two datasets

Cleans the data

Stores it in a SQLite database

2- Project Workspace - Machine Learning Pipeline

Loads data from the SQLite database

Splits the dataset into training and test sets

Builds a text processing and machine learning pipeline

Trains and tunes a model using GridSearchCV

Outputs results on the test set

Exports the final model as a pickle file

3- Flask Web App

When a user inputs a message into the app, the app returns classification results for all 36 categories.




# Files

This repository contains four files:

1- Readme file, which contains a short description of the project and a summary of the results.

2- messages.csv file, which is one of the datasets provided by Figure Eight as csv format.

3- categories.csv file, which is one of the datasets provided by Figure Eight as csv format.

4- ETL Pipeline Preparation .ipynb, which contains the Python source code of ETL pipeline.

5- ML Pipeline Preparation .ipynb, which contains the Python sourse code of ML Pipeline.

6- Workspace foulder which consists of web app files




# Screenshots

![Screenshot1](https://user-images.githubusercontent.com/94007036/193726436-8200e86d-cc46-407c-a2e0-7050f39fc350.png)

![Screenshot2](https://user-images.githubusercontent.com/94007036/193726453-2d96de28-8546-4239-9693-39c8422e3fe0.png)



# Acknowledgement

This project is completed as part of Udacity Data Scientist Nanodegree by using Figure Eight dataset.
