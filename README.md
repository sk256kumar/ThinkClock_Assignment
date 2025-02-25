# README - Battery Data Analysis & Machine Learning Model

## Overview
This project analyzes Li-ion battery data, performs exploratory data analysis (EDA), visualizes incremental capacity trends, and trains a machine learning model to predict battery capacity.

## Features
- **Exploratory Data Analysis (EDA)**: Summary statistics and pairwise plots.
- **Incremental Capacity Analysis**: Computes and visualizes dQ/dV vs. Voltage.
- **3D Visualization**: Shows incremental capacity peaks over cycle count.
- **Feature Engineering**: Includes moving averages of voltage, current, and temperature.
- **Machine Learning**: Trains a Random Forest model with hyperparameter tuning.
- **Model Evaluation**: Uses Mean Absolute Error (MAE) and R² score to assess performance.

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## How to Run
1. Install dependencies using:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Load the dataset (`00007.csv`).
3. Run the script to perform analysis and train the model.

## Expected Output
- Summary statistics and pair plots.
- 2D plot of dQ/dV vs. Voltage.
- 3D plot of incremental capacity peaks.
- Best hyperparameters and model evaluation metrics.

## Author
SaiKumar Burra

