# Electric Vehicle Range Prediction Project

## Project Overview

This project focuses on building a machine learning model to accurately predict the driving range of Electric Vehicles (EVs). Using real-world EV specifications, I've developed a robust predictive tool that helps understand how different vehicle characteristics influence their range.

## Key Highlights

* *Data Analysis:* Explored a dataset of EV specifications, cleaning and preparing it for modeling.
* *Powerful Prediction:* Developed a *Gradient Boosting Regressor model* that achieved an impressive *99% accuracy (R² score)* in predicting EV range.
* *Key Factors Identified:* Discovered that *Battery Capacity, **Efficiency, and **Fast Charging* are the most crucial factors determining an EV's range.
* *Interactive Dashboard:* Created a dynamic dashboard (using Power BI, and also provided code for a web-based version) to visualize model performance, range distributions, and the impact of key features.

## What's Inside?

* EV_cars.csv: The raw dataset used for the project.
* EV_range_predictions_for_PowerBI.csv: The processed data, including actual and predicted ranges, ready for dashboard visualization.
* ev_range_prediction_script.py: The Python code covering data loading, cleaning, EDA, model training, evaluation, and feature importance analysis.
* *Power BI Dashboard:* Instructions and data to build an interactive dashboard in Power BI Desktop (.pbix file not included as it's a proprietary format).
* *Web-based Dashboard (HTML/CSS/JS):* Code for a browser-based dashboard alternative.

## How to Explore

1.  *Run the Python script:* Execute ev_range_prediction_script.py to see the data analysis and model building process.
2.  *View the Dashboard:*
    * *Power BI:* Import EV_range_predictions_for_PowerBI.csv into Power BI Desktop and follow the provided instructions to build the interactive dashboard.
    * *Web-based:* Place index.html, style.css, script.js, and EV_range_predictions_for_PowerBI.csv in the same folder, then run a simple local web server (python -m http.server 8000) and open http://localhost:8000/index.html in your browser.

This project demonstrates a hands-on approach to data science, from raw data to actionable insights!

