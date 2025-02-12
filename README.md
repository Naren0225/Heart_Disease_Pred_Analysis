# Exploratory Data Analysis (EDA) for Heart Disease Prediction

## Overview
This project performs **Exploratory Data Analysis (EDA)** on a heart disease dataset to understand key patterns and relationships between features. The dataset is sourced from the **Cleveland database**, available on:
- [Kaggle](https://www.kaggle.com/ronitf/heart-disease-uci)
- [UC Irvine's Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)

The insights from this analysis will be used for predictive modeling in subsequent steps.

## Project Structure
- **Exploratory Data Analysis (EDA)** (this notebook)
- **Modeling** (to be linked in the future)
- **Evaluation and Conclusion** (to be linked in the future)

## Installation
To run this project locally, install the required dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-eda.git
   cd heart-disease-eda
   ```
2. Run Jupyter Notebook:
   ```bash
   jupyter notebook Exploratory-Data-Analysis.ipynb
   ```

## Key Features of the Analysis
- **Data Cleaning**: Handling missing values and checking for inconsistencies.
- **Feature Analysis**: Understanding distributions, correlations, and outliers.
- **Visualization**: Histograms, box plots, scatter plots, and correlation heatmaps.
- **Statistical Insights**: Identifying significant predictors of heart disease.

## Dataset Information
The dataset contains patient records with attributes such as:
- Age, Sex, Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol Levels (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate (thalach)
- Exercise-Induced Angina (exang)
- ST Depression (oldpeak)
- Thalassemia (thal)

## Results and Insights
- Initial findings suggest strong correlations between certain features (e.g., **cholesterol levels** and **chest pain type**) with heart disease risk.
- **Visualization techniques** help uncover hidden trends in the dataset.
- These insights will be used for **machine learning model development** in future steps.

