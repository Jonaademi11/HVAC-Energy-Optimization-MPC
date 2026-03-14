# HVAC Energy Optimization using Data Analysis and MPC

This project analyzes energy consumption in HVAC systems using the **UCI Appliances Energy Prediction dataset**.  
The goal is to understand which internal and external factors influence energy consumption and to simulate a simplified **Model Predictive Control (MPC)** strategy to reduce energy usage.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset
The dataset used in this project comes from the UCI Machine Learning Repository:
Appliances Energy Prediction Dataset.

It contains real measurements of:
- Indoor temperatures (T1–T9)
- Outdoor temperature
- Humidity
- Energy consumption
- Weather conditions

## Project Objectives

1. Identify internal and external factors that influence HVAC energy consumption.
2. Analyze the relationship between indoor temperature and external conditions.
3. Simulate a simplified **Model Predictive Control (MPC)** strategy to reduce energy consumption.

## Analysis Performed

- Descriptive statistical analysis
- Data visualization (histograms, scatter plots, correlation matrix)
- Linear regression modeling
- Energy consumption pattern analysis
- Simplified MPC simulation for energy optimization

## Results

The analysis shows that:
- External factors such as outdoor temperature influence energy consumption.
- Indoor temperature remains relatively stable.
- The simplified MPC strategy reduces average energy consumption.

## Project Structure

- `notebooks/` – Jupyter notebooks containing analysis
- `data/` – dataset used for analysis
- `images/` – generated graphs
- `report/` – research report

## Author

Jona Ademi  
Computer Science Graduate  
Master’s Student in Control Systems and Artificial Intelligence
