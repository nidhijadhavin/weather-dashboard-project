Weather Analysis Dashboard using Machine Learning and Streamlit

This project analyzes historical weather data and uses a Random Forest Regression model to predict temperature based on humidity, pressure, visibility, and wind speed.
A simple Streamlit dashboard can also be created to visualize insights and predictions.

Project Features:
Exploratory Data Analysis
Handling missing values
Feature engineering
Trend analysis
Correlation heatmaps

Machine Learning Model:
Random Forest Regressor
Model performance:
MAE approx 0.017
RMSE approx 0.056
R2 score approx 0.9999
Trained model saved as temperature_model.pkl

Dashboard (optional):
Sidebar inputs
Real time temperature prediction
Charts and visualizations

Project Structure:
weather-dashboard-project
weatherHistory.csv
temperature_model.pkl
notebook.ipynb
README.md

How to Run:
Install required libraries
pip install pandas numpy scikit-learn streamlit
Run the notebook
jupyter notebook
Run the dashboard (if using Streamlit)
streamlit run app.py

Dataset Information
Contains historical weather data with temperature, humidity, pressure, visibility, wind speed, and weather summary.
