# F1-Predictions
Welcome to the F1 Qualifying Time Prediction project! This notebook uses real-time and historical qualifying data from Formula 1 (via the FastF1 API) to analyze and predict Q3 lap times using linear regression and domain-specific performance factors.

🚀 Project Overview
This project focuses on:

Fetching qualifying data for the 2024–2025 Formula 1 seasons using FastF1

Cleaning and visualizing Q1, Q2, and Q3 lap times

Building a linear regression model to predict Q3 times based on Q1 and Q2 performance

Enhancing predictions with team and driver performance multipliers

Simulating Q3 qualifying results for the upcoming 2025 Japanese Grand Prix

📁 Files in Repository
File	Description
f1_qualifying_prediction.ipynb	Main Jupyter Notebook with data fetching, cleaning, visualization, modeling, and predictions
README.md	This file – documentation and instructions for the project
requirements.txt	List of required Python packages
cache/	Directory to store FastF1 cached data (created at runtime)


Main Libraries Used:

fastf1

pandas, numpy

matplotlib, seaborn

scikit-learn
