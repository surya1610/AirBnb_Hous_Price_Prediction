# DATA_606 - Capstone Project
Author : Surya Narayana Reddy Chintacunta
Semester : Spring 2023
Campus ID : TO87136

# Project Title : Airbnb House Price Prediction
# Problem Statement
- Airbnb is an online marketplace and hospitality service that connects individuals who have space to rent, typically their homes or apartments, with travelers seeking accommodations. 
- The concept behind Airbnb is to provide an alternative to traditional hotels and offer a more personalized and authentic travel experience.
- Being such a gaint in its domain, Airbnb should maintain its customers with atmost satisfaction.
- Airbnb pricing is important to get right, particularly in big cities like London where there is lots of competition and even small differences in prices can make a big difference.
- It is also a difficult thing to do correctly — price too high and no one will book. Price too low and you’ll be missing out on a lot of potential income.
# Objective
- Airbnb began in 2008 when two designers who had space to share hosted three travelers looking for a place to stay.
- Now, millions of hosts and travelers choose to create a free Airbnb account so they can list their space and book unique accommodations anywhere in the world. AirBnB provides a predictive pricing tool to hosts, but the tool has received complaints for not being accurate enough.
- Some hosts even believe AirBnB may be artificially decreasing prices to keep new customers coming into the platform. Hence i decided to develop a predictive model for AirBNB prices.
# Data Source
- Since 2008, guests and hosts have used Airbnb to travel in a more unique, personalized way. 
- As part of the Airbnb Inside initiative, this dataset describes the listing activity of homestays in New York City
- Listings, including full descriptions and average review score Reviews, including unique id for each reviewer and detailed comments Calendar, including listing id and the price and availability for that day
The data source is mentioned below:

- http://insideairbnb.com/explore/
- Size : 35.91 MB
- Rows : 1.02 M
- Columns : 26
# Implemented Solution
- The main motive of the project is to predict the Airbnb listing prices. Hence "Price" is the unit for my analysis. 
- Implemented the first phase which is Data preprocessing and EDA using Matplotlib, Seaborn, and Plotly for visualizations.
- Used Data Preprocessing,Handling missing values and Encoding the data for various steps in the project.
- Used Logistic Regression, Decision Tree and Random Forest and Ridge regressor machine learning models to predict the “Price”based on input features.
# Data Cleaning
Data Cleaning was done in multiple steps:
- Dropped features having more than 50% of null values.
- Dropped records in the feature "Availability" where the value range is not in the range "0" and "365".
- Filled missing values in some features using "Mean" and "Median" method.
- Removed Duplicate records from the datasets.
# Exploratory Data Analysis
<img width="354" alt="image" src="https://github.com/surya1610/Surya_Data_606/assets/53937677/f7af5f51-8d49-4159-b77a-211aefbb8c55">





