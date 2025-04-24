# 🚲 Bike Sharing Demand Prediction

## 📌 Project Type
**Regression Analysis**  

## 📝 Project Summary

This project aims to enhance public mobility in urban areas through smarter management of bike-sharing systems. These systems require accurate demand forecasts to maintain a balanced supply across various stations. By using historical data—such as temperature, date, and time—this project builds predictive models to estimate the number of bikes that will be rented in Seoul.

---

## 🎯 Problem Statement

Bike-sharing programs often struggle with demand-supply mismatches. This project uses machine learning to predict bike rental counts based on time and environmental factors, enabling proactive resource allocation and improved user satisfaction.

---

## ✅ Key Milestones

### 1. Data Preparation
- Dataset: ~8,760 records with 14 features.
- Tasks included:
  - Data import and EDA (Exploratory Data Analysis)
  - Handling of missing values and outliers
  - Data transformation for model compatibility
  - Square root normalization to tackle skewed target values

### 2. Model Building & Evaluation
- Trained **11 different ML models**
- Key evaluation metrics:
  - **R² Score** for goodness-of-fit
  - **RMSE** for error measurement
- Focus on scale-independent evaluation for robust model comparison

---

## 🛠️ Tools & Technologies Used
- Python
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Jupyter Notebook

---

## 📊 Outcomes
- Successfully identified the most accurate model for predicting bike demand
- Offered actionable insights for bike-sharing system managers

---

## 🚀 How to Run
1. Clone the repo
2. Open `BSD.ipynb` in Jupyter or any notebook-compatible editor
3. Run all cells sequentially
4. Ensure all required libraries are installed:
   ```bash
   pip install -r requirements.txt
