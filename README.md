## 📊 Data Visualization & Predictive Modeling Projects

This repository contains two end-to-end data projects implemented in Python using Google Colab:
1. Iris Flower Classification – Exploratory Data Analysis (EDA) and regression-based prediction of flower species.
2. Zomato Restaurant Cost Prediction – Data cleaning, feature engineering, and a decision tree model to predict approximate dining costs for two people.

## 📌 Project Overview

### 🌸 1. Iris Flower Prediction

Goal: Predict species of flower based on petal & sepal dimensions.

### Steps Performed:
  - Imported & explored the Iris dataset.
  - Conducted data visualization using scatter plots, histograms, KDE plots, box plots, and pair plots.
  - Built Linear Regression and Multivariable Linear Regression models.
  - Evaluated relationships between features and predicted flower species.

### 🍴 2. Zomato Restaurant Cost Prediction

Goal: Predict approximate cost for two people in restaurants using the Zomato dataset.

Dataset: ~23,000 records with 17 attributes (location, cuisines, ratings, etc.).

## Steps Performed:
  - Data Cleaning: Removed duplicates, null values, and redundant columns.
  - Feature Engineering: Encoded categorical variables (Label Encoding).
  - Modeling: Applied Decision Tree Classifier to predict restaurant costs.
  - Result: Achieved ~99.9% accuracy on the training dataset. (Note: accuracy may be inflated due to overfitting.)

## 🛠️ Technologies & Libraries Used
  Python
  Pandas, NumPy – Data manipulation
  Matplotlib, Seaborn – Visualization
  Scikit-learn – Machine Learning (Regression, Decision Tree, Label Encoding)
  Google Colab – Development environment

## 📈 Visualizations

The notebook includes multiple visualization techniques for exploratory data analysis (EDA):
  - Scatter Plots
  - Histograms
  - Pair Plots
  - KDE Plots
  - Box Plots
  - Heatmaps
  - Subplots
  - Bar Graphs

### 🚀 How to Run

Clone the repository:

```
git clone https://github.com/your-username/Data-Visualization-ML-Projects.git
cd Data-Visualization-ML-Projects
```

Open the notebook in Google Colab or Jupyter Notebook.

Install dependencies (if running locally):
pip install pandas numpy matplotlib seaborn scikit-learn

### Run all cells to reproduce results.

📂 Repository Structure
├── iris_flower_analysis.ipynb       # Iris dataset visualization & regression
├── zomato_cost_prediction.ipynb     # Zomato dataset cleaning & decision tree
├── data/                            # (Optional) Store datasets here
└── README.md                        # Project documentation

## 📊 Results

Iris Prediction: Regression captured strong relationships between petal/sepal size and species classification.

Zomato Cost Prediction: Decision Tree achieved ~99.9% accuracy in predicting restaurant cost categories.
