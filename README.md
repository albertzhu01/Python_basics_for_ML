# Python Basics for Data Science and ML

Project from IBM's Data Science and Machine Learning Capstone Project course on EdX

## Overview

Data Science and ML project for analyzing factors associated with the success rate of first stage landings of SpaceX rocket launches

## Project Components

### Data Collection

Various data on SpaceX's rocket launches (including date, location, payload mass, etc.) were collected from the SpaceX API and preprocessed & formatted using Pandas (Final_notebook_1.ipynb).

### Data Wrangling

Many aspects of the data were analyzed (including number of launches at different sites and in different orbits). Additionally, class labels were created for the first stage landing outcome of each launch: 0 for failed landing and 1 for successful landing (Data Wrangling notebook).

### Exploratory Data Analysis / Data Visualization

Relationships between various features of the launches (e.g. Payload Mass, Orbit Type, etc.) were analyzed. Furthermore, one-hot encodings of the features were created for later use in ML prediction (EDA with Data Visualization notebook).

### Exploratory Data Analysis / Interactive Visual Analytics

Relationships between launch site and launch outcome were interactively analyzed using Folium (Interactive Visual Analytics notebook).

### Machine Learning Prediction

Several machine learning models (logistic regression, SVM, decison tree, and KNN) were trained on features of the launches (date, location, payload mass, etc.) to predict the outcomes of different launches. The decision tree model was found to perform with the highest accuracy while the three other models had significant difficulty classifying failed launches.
