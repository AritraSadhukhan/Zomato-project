# Zomato-project
Project Overview

This project focuses on analyzing the Zomato restaurant dataset to uncover meaningful insights and trends. The goal is to explore factors affecting restaurant ratings, pricing, and geographical distribution, providing actionable insights for restaurant owners and food enthusiasts.

Dataset Information

The dataset used in this analysis contains detailed information about restaurants listed on the Zomato platform. Key attributes include:

Restaurant Name

Location

Cuisines

Average Cost for Two

Rating

Number of Votes

Reviews Count

Data Preprocessing

Before analysis, the dataset was cleaned and prepared:

Handling missing values.

Converting data types for numerical analysis.

Removing duplicates and standardizing text.

Geolocation data was parsed for geographical insights.

Exploratory Data Analysis (EDA)

Key questions explored during EDA:

What are the top cuisines offered in various locations?

How does the average cost for two vary by city?

Which locations have the highest-rated restaurants?

What is the distribution of restaurant ratings?

Visualizations include:

Geographical heatmaps of restaurant density.

Bar charts of top cuisines and locations.

Histograms of average costs and ratings.

Feature Engineering

New features were derived from the existing dataset to enhance the analysis:

Price Range Category – Grouping average costs into categories.

Rating Category – Binning ratings into segments (e.g., Excellent, Good, Average).

Model Building & Evaluation

Predictive models were built to forecast restaurant ratings and price categories:

Linear Regression for price prediction.

Random Forest for rating classification.

Evaluation Metrics:

R-squared, Mean Absolute Error (MAE), and Confusion Matrix were used for assessing model performance.

Results & Insights

Restaurants offering multi-cuisine menus tend to have higher ratings.

Average cost is significantly influenced by the restaurant's location.

Certain areas are densely populated with highly-rated restaurants, indicating competitive food hubs.

Future Work

Future improvements may include:

Integrating more real-time data for dynamic analysis.

Applying advanced ML models for better predictions.

Exploring customer review sentiments for deeper insights.

Dependencies

Python 3.9+

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Folium (for map visualizations)
