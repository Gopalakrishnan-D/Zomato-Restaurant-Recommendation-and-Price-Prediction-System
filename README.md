# Zomato-Restaurant-Recommendation-and-Price-Prediction-System

# Problem Statement:
Develop a web-based application similar to Zomato, which allows users to select restaurants based on location and cuisine and provides average price predictions for two people dining based on various features. The project should include data structuring, model building, and interactive visualizations, and the web app should be hosted on AWS EC2.
Business Use Cases:
Restaurant Discovery: Suggesting restaurants based on user preferences for location and cuisine.
Price Estimation: Predicting the average cost for two people based on restaurant features such as location, cuisine, and facilities.
Personalized Recommendations: Providing users with restaurant recommendations based on features like ratings, location, and cuisines.
Operational Insights: Offering insights for restaurant owners on pricing trends, ratings, and user preferences.

# Approach:
# Data Management:
- Upload the provided Zomato dataset (in JSON format) into an AWS S3 bucket.
- Pull the dataset from S3 and preprocess it for structuring.
- Store the structured data into AWS RDS in SQL format.

# Model Development:
- Extract relevant features from the dataset (e.g., location, cuisine, average cost, ratings).
- Build a machine learning model to predict the average cost for two people based on these features.
-Train, evaluate, and save the model for deployment.

# Web Application:

- Build an interactive Streamlit web application.
- The app should display restaurant options based on user input (location, cuisine) and predict the average price for two people.
- Add interactive visualizations for restaurant ratings, cuisines, and price range distribution.

# Deployment:

Host the Streamlit web application on an AWS EC2 instance for public access.

# Results: 
- Machine Learning Model: A model that predicts the average cost for two people based on features like location, cuisine, and restaurant ratings.
- Streamlit Web App: An interactive, user-friendly web interface that provides restaurant recommendations and price predictions.
- Visualizations: Graphical representations of restaurant distributions, price ranges, and user preferences.
- Deployment: A fully functional, publicly accessible web application hosted on AWS EC2

# Project Evaluation metrics:

Prediction Accuracy: RMSE, MAE for the average price prediction model.

# User Engagement: 

Feedback and interaction with the recommendation system.
Application Performance: Response time, uptime, and smoothness of interaction in the deployed web app.
Data Insights: Correctness of the restaurant suggestions and price predictions.

# Technical Tags:
-- Technologies: Python, AWS S3, AWS RDS, AWS EC2, Streamlit
Libraries: pandas, scikit-learn, matplotlib, seaborn, SQLAlchemy, boto3
Machine Learning: Regression models (Linear Regression, Random Forest)
Data Processing: JSON handling, data structuring, SQL
Visualization: Interactive plots using Streamlit and matplotlib
