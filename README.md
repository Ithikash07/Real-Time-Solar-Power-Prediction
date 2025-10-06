# Real-Time-Solar-Power-Prediction

Real-Time Solar Power Prediction for Namakkal Region

This project predicts short-term solar power generation using weather and solar irradiance data from preferred regional place. Historical CSV files (2016-2020) are merged and cleaned, with features like temperature, GHI, and humidity used to train Random Forest models. The system predicts upcoming values every 15 minutes, estimates solar power output, and stores results in a MySQL database for dashboard visualization in Grafana.

Features

Data processing and merging for multiple years

Random Forest regression for predicting temperature, GHI, and humidity

Automatic 15-minute interval forecasting and MySQL storage

Grafana dashboard for live monitoring and analysis

Technologies

Python, Pandas, Scikit-learn, MySQL, Grafana
