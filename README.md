Titanic Survival Prediction
Chapter 1: Introduction & Business Understanding
"A data scientist doesn't just analyze data—they ask questions inspired by the world around them."

Project Motivation
Last night, I watched Titanic (1997), one of the most iconic films ever made. Although the movie tells a fictional love story between Jack Dawson and Rose DeWitt Bukater, it is based on the real sinking of the RMS Titanic on April 15, 1912.

While watching the film, several questions came to mind:

Were women really more likely to survive?
Did children have a better chance of survival?
Did being wealthy increase the probability of surviving?
Were third-class passengers truly trapped below deck?
Did traveling with family improve or reduce survival chances?
The movie presents these ideas emotionally, but as a data scientist, I wanted to determine whether the historical passenger data supports these narratives.

Instead of relying solely on the movie, this project uses the famous Titanic dataset to explore the characteristics of passengers and identify the factors associated with survival.

This notebook focuses on Exploratory Data Analysis (EDA), where I will investigate the data, identify meaningful patterns, discover relationships between variables, and generate hypotheses that will later be tested using machine learning models.

Business Problem
Imagine being hired by the White Star Line before the Titanic's maiden voyage.

The company wants to understand which passenger characteristics are most strongly associated with survival during a maritime disaster. These insights could be used to improve future safety policies and evacuation procedures.

Our objective is to analyze historical passenger information and ultimately build a machine learning model capable of predicting whether a passenger would survive based on their characteristics.

Problem Statement
Can we predict whether a passenger survived the Titanic disaster using information such as:

Age
Gender
Passenger Class
Ticket Fare
Family Members
Cabin Information
Embarkation Port
Type of Machine Learning Problem
This is a Supervised Machine Learning problem because the historical outcomes are already known.

Specifically, it is a Binary Classification problem.

Target Variable:

Survived

0 = Passenger did not survive
1 = Passenger survived
Project Workflow
This project will follow the complete Data Science lifecycle.

Business Understanding
Exploratory Data Analysis (Current Notebook)
Data Cleaning
Feature Engineering
Data Preprocessing
Machine Learning Model Development
Model Evaluation
Hyperparameter Tuning
Feature Importance Analysis
Conclusions
Questions I Want the Data to Answer
Watching the movie inspired several hypotheses that I would like to validate using data.

Hypothesis 1
Women had a higher survival rate than men.

Hypothesis 2
Children were more likely to survive.

Hypothesis 3
Passengers traveling in First Class had a much greater chance of survival.

Hypothesis 4
Passengers who paid higher ticket fares had better survival rates.

Hypothesis 5
Passengers traveling with family had different survival rates than passengers traveling alone.

Hypothesis 6
Cabin location (deck level) may have influenced survival.

Hypothesis 7
Passenger characteristics interact with one another, meaning survival was influenced by multiple factors rather than a single variable.

Success Criteria
By the end of this project I aim to:

✔ Understand the dataset

✔ Discover hidden patterns

✔ Build meaningful features

✔ Train multiple machine learning models

✔ Explain which variables were most important for predicting survival

✔ Compare whether the historical data supports the story portrayed in the movie
