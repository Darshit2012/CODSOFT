# Sales Prediction

## Overview  
The dataset contains advertising data with sales (in thousands of units) for a particular product, along with advertising budgets (in thousands of dollars) for TV, radio, and newspaper media.  
The task was to analyze this data and suggest a marketing plan for future sales by building robust regression models and selecting the best-performing one.

The project was implemented using **Python** with **Pandas, NumPy, Scikit-learn, and Seaborn** for analysis and model development.

---

## Project Details  
- **Objective**: Predict sales based on the given advertising expenditures.  
- **Models Used**:  
  - KNN Regression  
  - Decision Tree Regression  
  - ElasticNet Regression  
  - Lasso Regression  
  - Linear Regression  
  - Ridge Regression  
  - XGBoost Regression  
  - Random Forest Regression  
  - Gradient Boosting Regression  

- **Best Model**: Gradient Boosting Regression  
- **Accuracy Achieved**: 96%  
- **MSE Achieved**: 1.245  

---

## Key Features  
- Analyzed the Sales Prediction dataset through data visualization, preprocessing, and machine learning model selection.  
- Identified dataset characteristics such as relationships and noise that affect model performance.  
- Observed **outliers** in the *Newspaper* category, while TV and Radio had none.  
- **Gradient Boosting Regression** outperformed all other models with the highest accuracy (96%) and lowest MSE (1.245).  
- **Random Forest Regression** came second with 95% accuracy (MSE = 1.496), followed by **XGBoost Regression** with 93.9% accuracy (MSE = 1.880).  
- The best-performing Gradient Boosting model’s sales predictions were saved for deployment.  

---

## Model Performance Summary  

| Model                     | MSE   | R² Score  |
|----------------------------|-------|-----------|
| Gradient Boosting Regressor | 1.245 | 0.9597    |
| Random Forest Regressor     | 1.496 | 0.9516    |
| XGBoost Regressor           | 1.880 | 0.9391    |
| Linear Regression           | 2.908 | 0.9059    |
| Lasso Regression            | 2.909 | -         |
| ElasticNet Regression       | 2.910 | -         |
| Decision Tree Regressor     | 3.011 | 0.9025    |
| KNN Regressor               | 3.116 | 0.8991    |
| Ridge Regression            | 2.908 | -         |

---

👨‍💻 Developed as part of the **Data Science Internship at CODSOFT**  
