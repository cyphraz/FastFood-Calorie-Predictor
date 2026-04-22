# Fast Food Nutrition & Calorie Predictor
A machine learning project that analyses nutritional data from major fast food
chains to predict calorie content using regression models. Built with Python
as part of a Data Science and Machine Learning module.

---

## About
This project explores the nutritional composition of fast food menu items
across multiple chains including McDonald's, Burger King, and Taco Bell.
Using machine learning regression models, the project predicts calorie content
based on macronutrients such as Total Fat, Carbohydrates, and Protein.

---

## Dataset
- **Name:** Fast Food Nutrition Menu V3
- **Source:** Kaggle (Public Dataset)
- **File:** `FastFoodNutritionMenuV3.csv`
- **Dataset License:** Database Contents License (DbCL) via Kaggle
---

## Project Contents
- `Coursework1.ipynb` — Main Jupyter notebook (EDA, preprocessing, models)
- `FastFoodNutritionMenuV3.csv` — Dataset sourced from Kaggle
- `license.txt` — License information

---

## Models & Results

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression | 22.26 | 36.35 | 0.979 |
| Gradient Boosting | 17.06 | 24.49 | 0.990 |
| **Random Forest** ⭐ | **11.98** | **22.88** | **0.992** |

Random Forest achieved the best overall performance.

---

## Key Findings
- Total Fat, Carbohydrates, and Protein are the strongest predictors of calories
- Random Forest outperforms linear models by capturing non-linear nutrient interactions
- Machine learning can assist restaurants and consumers in making more health-conscious decisions

---

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn
- scikit-learn

Install dependencies:
