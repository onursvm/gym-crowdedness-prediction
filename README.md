## 📓 Kaggle Notebook

Explore the complete analysis and machine learning workflow on Kaggle.

<p align="center">
  <a href="https://www.kaggle.com/code/onursvm/gym-crowdedness-prediction">
    <img src="https://img.shields.io/badge/🚀%20Open%20on-Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white" alt="Open on Kaggle"/>
  </a>
</p>

# 🏋️ Gym Crowdedness Prediction

A machine learning project that analyzes gym attendance patterns and predicts the number of people in a gym based on factors such as time, day of the week, temperature, holidays, and semester periods.

## 📌 Project Overview

This project focuses on understanding gym occupancy patterns through **Exploratory Data Analysis (EDA)** and building machine learning models to predict the number of people in the gym.

The dataset contains information about gym attendance along with environmental and calendar-related features. Several regression algorithms are trained and evaluated to determine which model performs best for predicting gym occupancy.

## 🎯 Objectives

* Analyze gym attendance patterns.
* Explore the relationship between gym occupancy and different variables.
* Visualize hourly and daily attendance trends.
* Investigate the effects of temperature, holidays, and semester periods.
* Build multiple regression models.
* Compare model performances using different evaluation metrics.
* Optimize selected models using `RandomizedSearchCV`.

## 📊 Exploratory Data Analysis

The project includes several visualizations to understand the dataset:

* Average number of people by hour
* Average number of people by day of the week
* Relationship between temperature and gym occupancy
* Gym attendance during holidays
* Gym attendance at the beginning of the semester
* Gym attendance during the semester
* Correlation matrix of numerical features

These analyses help identify the variables that have the strongest relationship with gym attendance.

## 🤖 Machine Learning Models

The following regression algorithms were implemented and compared:

* Linear Regression
* Lasso Regression
* Ridge Regression
* K-Nearest Neighbors Regressor
* Decision Tree Regressor
* Random Forest Regressor

For model optimization, **RandomizedSearchCV** was used to search for better hyperparameter combinations for:

* K-Nearest Neighbors
* Random Forest

## ⚙️ Machine Learning Pipeline

The general workflow of the project is:

```text
Dataset
   ↓
Data Loading
   ↓
Data Inspection & Cleaning
   ↓
Date Feature Extraction
   ↓
Exploratory Data Analysis
   ↓
Feature / Target Separation
   ↓
Train-Test Split
   ↓
Feature Scaling
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Hyperparameter Optimization
   ↓
Final Model Comparison
```

## 📏 Evaluation Metrics

The models are evaluated using four different regression metrics:

### Mean Absolute Error (MAE)

Measures the average absolute difference between actual and predicted values.

### Mean Squared Error (MSE)

Measures the average squared difference between actual and predicted values.

### Root Mean Squared Error (RMSE)

The square root of MSE. Lower values indicate better performance.

### R² Score

Measures how well the model explains the variance in the target variable. Higher values indicate better performance.

## 🛠️ Technologies & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## 📁 Project Structure

```text
gym-crowdedness-prediction/
│
├── gym-crowdedness.ipynb
├── gym-crowdedness.csv
└── README.md
```

## 📓 Notebook

The complete analysis and machine learning implementation can be found in:

`gym-crowdedness.ipynb`

The notebook includes data preprocessing, visualization, model training, evaluation, and hyperparameter optimization.

## 📂 Dataset

The dataset used in this project is available on Kaggle:

**Kaggle Dataset:**
https://www.kaggle.com/datasets/nsrose7224/crowdedness-at-the-campus-gym

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/gym-crowdedness-prediction.git
```

Navigate to the project directory:

```bash
cd gym-crowdedness-prediction
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```text
gym-crowdedness.ipynb
```

## 📌 Key Takeaways

This project demonstrates a complete machine learning workflow, from data exploration and visualization to model comparison and hyperparameter optimization.

It also provides practical experience with **regression algorithms, feature preprocessing, model evaluation, and data-driven analysis**.

## 👨‍💻 Author

**Onur Sevim**

Computer Engineering Student | Software Engineering & Machine Learning Enthusiast

---

⭐ If you find this project useful, feel free to star the repository!
