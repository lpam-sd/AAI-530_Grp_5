# AAI-530_Grp_5

Tableau Dashboard Link:  https://public.tableau.com/views/Assignment7_1-FinalProjectNurseStressPredictionEDAAnalysis/Dashboard3?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


Nurse Stress Prediction using Wearable Sensors

Project Overview: 

This project explores stress prediction in nurses using data collected from wearable sensors. The dataset includes physiological signals such as EDA (Electrodermal Activity), Heart Rate (HR), and Temperature (Temp), recorded from nurses during their shifts. The goal is to analyze stress patterns, classify stress levels, and build predictive models using Machine Learning (ML) techniques.

Repository Contents:

This repository includes data preprocessing, exploratory data analysis (EDA), and machine learning models to predict stress levels. The key components are:

1. Data Cleaning & Preprocessing:
  * Loaded and cleaned the raw dataset.
  * Handled data inconsistencies.
  * Converted categorical variables and adjusted data types.
2. Exploratory Data Analysis (EDA):
  * Visualized trends in stress levels over time.
  * Examined relationships between physiological features and stress labels.
  * Identified patterns in nurse stress responses using Tableau dashboards.
3. Machine Learning Models:
  * Random Forest Model: Used to classify stress levels based on sensor data.
  * LSTM Model: Built to predict future stress levels using sequential patterns.
  * Confusion Matrix & Performance Metrics: Evaluated model accuracy and misclassifications.
4. Visualizations & Dashboard:
  * Status Visualization: Displays total nurses reporting data.
  * Summary Visualization: Tracks stress trends over time.
  * ML Model Performance: Shows predictions vs. actual stress levels.
  * Final Dashboard: Consolidates all insights in an interactive Tableau report.

    How to Use:
    1. Clone the repository
       git clone https://github.com/yourusername/nurse-stress-prediction.git
    2. Navigate to the project directory:
       cd nurse-stress-prediction
    3. Run the data cleaning and preprocessing scripts in Jupyter Notebook or Python.
    4. View the Tableau dashboards for insights into stress levels.
    5. Explore the ML model predictions and evaluations.
   
    Tools & Technologies:
      * Python (Pandas, NumPy, Scikit-Learn, TensorFlow)
      * Tableau (Data Visualization)
      * Jupyter Notebook
      * GitHub (Version Control)
