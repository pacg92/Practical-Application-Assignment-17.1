# Practical Application Assignment 11.1

## Summary
This project explores the key drivers that influence the price of used vehicles using a dataset of listings. The analysis applies data preparation, regression models, and feature importance assessment to support decisión making for used car dealerships

## Files
- prompt_II.ipynb: Main notebook with the full data workflow, visualizations, modeling steps, and interpretation of results. [Click here to open the notebook](prompt_II.ipynb)
- README.md: Summary and documentation
- data/vehicles.csv: The 'data' folder contains the dataset 'vehicles.csv' used for the analysis. The dataset has information on 462K cars
- Images folder: Contains the images used in the .ipynb file

## Key Findings
- Odometer and vehicle age are consistently the most influential variables across all regression models
- Diesel fuel emerged as a positively associated factor with price in linear regression and decision tree models
- Decision Tree and KNN models captured nonlinear relationships better than linear regression
- The Decision Tree model achieved the lowest RMSE (~7300), indicating the best predictive performance
- No signs of overfitting were observed in the Decision Tree model, as training and test RMSE were similar