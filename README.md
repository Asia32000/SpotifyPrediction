# Spotify 2023 Hit Prediction – University Project
This repository contains a data science project developed as part of a university course. The goal of the project was to analyze the most streamed songs on Spotify in 2023 and to build predictive models estimating the number of streams based on various audio and metadata features.

## Project Overview

The dataset includes 953 songs with information such as artist name, release year, number of streams, and audio characteristics (e.g., danceability, energy, valence). The project includes:

Data exploration and visualizations
Feature correlation analysis
Data cleaning and preprocessing
Regression modeling to predict stream counts
Model comparison and evaluation


## Technologies Used

- Python 3
- Jupyter Notebook
- pandas
- matplotlib, seaborn
- scikit-learn
- NumPy
- Machine Learning Models

## Two regression models were trained and evaluated:

Decision Tree Regressor
Random Forest Regressor
Hyperparameters were optimized using GridSearchCV, and performance was assessed using R², MAE, MSE, and RMSE metrics.


## Results

The Random Forest Regressor achieved better performance compared to the Decision Tree model:

**Random Forest Regressor**
- R²: 0.705
- MAE: 199,673,512
- RMSE: 308,446,801

**Decision Tree Regressor**
- R²: 0.534
- MAE: 217,525,615
- RMSE: 387,316,624
  
These results indicate that the Random Forest model provides more accurate predictions of stream counts based on song attributes.
