# Bike Sharing Demand Prediction

This project predicts daily bike-sharing demand using linear regression, based on the UCI Bike Sharing Dataset.

## Dataset
- Source: [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)
- File: `day.csv` (place it in the project root or download from the source)

## Requirements
- Python 3.8+
- Install dependencies: `pip install -r requirements.txt`

## Usage
1. Clone the repository: `git clone https://github.com/your-username/your-repo-name.git`
2. Place `day.csv` in the project root.
3. Run the script: `python bike_sharing_prediction.py`

## Features
- Exploratory Data Analysis (EDA) with visualizations
- Feature engineering (dummy variables, scaling)
- Linear regression with feature selection (RFE)
- Model diagnostics (VIF, residuals, R², MSE)

## Output
- Visualizations: pairplots, boxplots, correlation heatmap, residual plots
- Model performance metrics: R², MSE