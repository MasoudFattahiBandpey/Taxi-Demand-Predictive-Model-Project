# Taxi-Demand-Predictive-Model-Project
Project Title
Taxi Demand Predictive Model for Manhattan and Surrounding Airports

Project Description
This project aims to address the challenges faced by Super Taxis, particularly the issue of misplaced taxis and long search times for pickups, which have been detrimental to profitability despite an increase in pickups. By utilizing data science and machine learning techniques, this project develops a predictive model to forecast taxi demand across Manhattan and its surrounding airports. The focus is on enhancing operational efficiency by identifying high-demand areas, thereby increasing the profitability of Super Taxis.

Objectives
Regional Focus: Analyze taxi demand in four custom-defined regions within Manhattan and the encompassing airports.
Demand Categorization: Develop a model that categorizes taxi demand into low, medium, and high levels.
Profitability Analysis: Conduct a comprehensive profitability study comparing revenue (fare) against cost (duration and distance) for each region.
Data Description
The project uses 12 months of taxi data, incorporating details such as pickup and drop-off locations, fares, distances, and durations. The data cleaning process involved removing outliers and erroneous entries, ensuring accuracy and reliability in the analysis.

Methodology
Data Importation and Cleaning: Utilization of importTaxiDataWithoutCleaning and filedatastore functions for data importation and preprocessing.
Feature Engineering: Identification and evaluation of relevant features, including the calculation of fare-to-distance ratios and handling of outliers.
Model Development: Training of a Classification Tree model to predict demand levels based on features like regions, day of the week, average distance, average fare, and average trip duration.
Evaluation: Analysis of the model's accuracy, precision, recall, and F1 score across different demand levels, with a detailed examination of feature importance.
