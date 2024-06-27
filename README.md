# Analyzing 911 Call Data

## Table of Contents
1. [Introduction](#introduction)
2. [Project Objectives](#project-objectives)
3. [Dataset Description](#dataset-description)
4. [Data Processing and Cleaning](#data-processing-and-cleaning)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Insights and Findings](#insights-and-findings)
7. [Methodology](#methodology)
8. [Tools and Technologies Used](#tools-and-technologies-used)
9. [Challenges and Solutions](#challenges-and-solutions)
10. [Conclusion](#conclusion)
11. [Future Work](#future-work)
12. [How to Run the Project](#how-to-run-the-project)
13. [Contributors](#contributors)
14. [References](#references)

## Introduction
For this capstone project we will be analyzing some 911 call data from [Kaggle](https://www.kaggle.com/mchirico/montcoalert). The data contains the following fields:

* lat : String variable, Latitude
* lng: String variable, Longitude
* desc: String variable, Description of the Emergency Call
* zip: String variable, Zipcode
* title: String variable, Title
* timeStamp: String variable, YYYY-MM-DD HH:MM:SS
* twp: String variable, Township
* addr: String variable, Address
* e: String variable, Dummy variable (always 1)

## Project Objectives
- Analyze the 911 call data to identify key trends and patterns.
- Visualize the data to uncover insights.
- Provide recommendations based on the findings.

## Dataset Description
Steps involved in data processing and cleaning:
1. Loading the data.
2. Handling missing values.
3. Formatting timestamps.
4. Encoding categorical variables.

## Data Processing and Cleaning
Explain the steps taken to clean and preprocess the data, including handling missing values, data transformations, and any other preprocessing techniques used.

## Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) is performed to visualize the distribution of the data and uncover patterns. This includes:
- Distribution of call reasons.
- Trend analysis over time.
- Geographical analysis of call locations.

## Insights and findings from the EDA:
- Peak times for 911 calls.
- Most common reasons for calls.
- Geographic hotspots for emergency incidents.

## Methodology
The methodology used in this project includes:
- Data collection.
- Data preprocessing.
- Exploratory Data Analysis.
- Visualization.

## Tools and Technologies Used
The project uses the following tools and technologies:
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Challenges and Solutions
Challenges faced during the project and their solutions:
- Handling large datasets: Used efficient data processing techniques.
- Missing data: Implemented strategies to handle missing values effectively.

## Contributors
Guillermo Del Rio

## References
[Kaggle](https://www.kaggle.com/mchirico/montcoalert).