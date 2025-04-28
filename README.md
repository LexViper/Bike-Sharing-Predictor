# BikeSharingPredictor 🚲📊

Welcome to **BikeSharingPredictor**, a data science project that predicts daily bike-sharing demand using linear regression! This project analyzes the UCI Bike Sharing Dataset to uncover patterns and build a predictive model for bike rentals based on weather, seasonality, and other factors. Perfect for data science enthusiasts and urban mobility nerds! 😎

## 🎯 Project Overview

The goal of this project is to predict the number of bike rentals (`cnt`) in a bike-sharing system using features like temperature, humidity, season, and more. It’s built with Python and leverages a full data science pipeline, including exploratory data analysis (EDA), feature engineering, and linear regression modeling.

- **Dataset**: UCI Bike Sharing Dataset (`day.csv`)
- **Techniques**: Linear Regression, Feature Selection (RFE), Scaling, Dummy Variables
- **Libraries**: `pandas`, `numpy`, `scikit-learn`, `statsmodels`, `seaborn`, `matplotlib`

## 📈 Features

- **Exploratory Data Analysis (EDA)**: Visualizations like pairplots, boxplots, and correlation heatmaps to uncover trends 📉
- **Data Preprocessing**: Handling missing values, creating dummy variables, and scaling features ⚙️
- **Model Building**: Linear regression with feature selection using Recursive Feature Elimination (RFE) 🧠
- **Diagnostics**: Variance Inflation Factor (VIF) for multicollinearity, residual analysis, and QQ plots 🔍
- **Evaluation**: R² scores and visualizations to assess model performance 🎯

## 🚀 Getting Started

Follow these steps to run the project locally:

### Prerequisites
- Python 3.8+ 🐍
- Git installed 📂
- The `day.csv` dataset (download from [UCI](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset) or include in the repo)

### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/BikeSharingPredictor.git
   cd BikeSharingPredictor
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # macOS/Linux
   venv\Scripts\activate     # Windows
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Add the dataset**:
   - Place `day.csv` in the project root or download it from the UCI link above.

### Usage
Run the main script to execute the analysis and see the results:
```bash
python bike_sharing_prediction.py
```

This will:
- Load and preprocess the data 🗂️
- Generate EDA visualizations 📊
- Train a linear regression model 🤖
- Output model diagnostics and performance metrics 📈

## 📂 Project Structure
```
BikeSharingPredictor/
├── bike_sharing_prediction.py  # Main script
├── day.csv                    # Dataset (optional, add to .gitignore if large)
├── requirements.txt           # Dependencies
├── README.md                  # This file
└── .gitignore                 # Git ignore file
```

## 📚 Dataset
The dataset (`day.csv`) contains daily bike rental counts with features like:
- `season`: Spring, Summer, Fall, Winter
- `temp`: Temperature
- `hum`: Humidity
- `weathersit`: Weather condition
- `cnt`: Target variable (bike rental count)

Source: [UCI Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset)

## 🛠️ Dependencies
See `requirements.txt` for the full list. Key libraries include:
- `numpy>=2.1.0`
- `pandas>=2.2.0`
- `matplotlib>=3.9.0`
- `seaborn>=0.13.0`
- `scikit-learn>=1.5.0`
- `statsmodels>=0.14.0`

## 📷 Sample Output
### Pairplot of numerical features
![Pairplot](https://raw.githubusercontent.com/LexViper/Bike-Sharing-Predictor/main/Output/plot.png)

### Correlation Heatmap
![Heatmap](https://raw.githubusercontent.com/LexViper/Bike-Sharing-Predictor/main/Output/Correlation.png)

### Actual vs Predicted scatter plot
![Actual vs Predicted](https://raw.githubusercontent.com/LexViper/Bike-Sharing-Predictor/main/Output/Actual%20vs%20Pred.png)

## 🤝 Contributing
Feel free to fork this repo, open issues, or submit pull requests to improve the project! 🚀

## 📬 Contact
Questions? Reach out via GitHub Issues or connect with me at thisisabhay.c@gamil.com.

