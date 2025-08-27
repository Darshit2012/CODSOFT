# 🎬 Movie Rating Prediction with Python

## 📌 Overview
This project develops a **predictive model** to estimate IMDB ratings of movies using machine learning techniques.  
The task is framed as a **regression problem**, where numerical ratings are predicted based on various features.  

**Key goals:**
- Predict IMDB ratings with high accuracy.  
- Identify **influential factors** (e.g., genre, director, actors) that affect ratings.  
- Provide **actionable insights** for movie production, casting, and marketing.  

---

## 🎯 Project Details
- **Objective**: Predict IMDB movie ratings with Python.  
- **Models Used**:  
  - Linear Regression  
  - Random Forest  
  - Decision Tree Regression  
  - Extended Gradient Boosting (XGBoost)  
  - Gradient Boosting  
  - Support Vector Regression (SVR)  
  - K-Nearest Neighbors (KNN)  

- **Best Model**: Random Forest  
- **Performance**:  
  - **R-squared Score**: **93.5%**  
  - **Mean Squared Error (MSE)**: **0.12**  
  - **Mean Absolute Error (MAE)**: **0.19**

---

## 🧹 Data Insights
- Extensive **data cleaning**: typo correction, handling missing & duplicate values.  
- **Temporal insights**: First entry from **1931**, with shortest movie of **45 minutes**.  
- **Actor analysis**: *Amitabh Bachchan* is the most frequent lead actor.  
- **Director analysis**: Identified top and least frequent directors.  
- **Votes & ratings**: Discovered best and worst-performing movies.  
- **Trends over years**: Distribution skewed towards **2015–2019**.  
- **Genre analysis**:  
  - *Drama* consistently dominant.  
  - *Comedy* and *Action* originated in **1953** and **1964**.  
- **Duration insights**: Shorter movies received higher ratings and votes.  
- **Statistical patterns**: Ratings and votes follow **Gaussian-like distributions**.  

---

## 📊 Model Performance

### Detailed Results
- **Linear Regression** → Accuracy: 78.47% | MSE: 0.40 | MAE: 0.47  
- **Random Forest** → Accuracy: 93.50% | MSE: 0.12 | MAE: 0.19  
- **Decision Tree Regression** → Accuracy: 90.77% | MSE: 0.17 | MAE: 0.13  
- **Extended Gradient Boosting (XGBoost)** → Accuracy: 91.41% | MSE: 0.16 | MAE: 0.26  
- **Gradient Boosting** → Accuracy: 82.56% | MSE: 0.33 | MAE: 0.41  
- **Support Vector Regression (SVR)** → Accuracy: 8.33% | MSE: 1.71 | MAE: 1.04  
- **K-Nearest Neighbors (KNN)** → Accuracy: 51.61% | MSE: 0.91 | MAE: 0.71  

---

### 📈 Comparison Table

| Regression Model            | Accuracy (%) | MSE  |
|------------------------------|--------------|------|
| Random Forest               | **93.50**    | 0.12 |
| Extended Gradient Boosting  | 91.41        | 0.16 |
| Decision Tree Regression    | 90.77        | 0.17 |
| Gradient Boosting           | 82.56        | 0.33 |
| Linear Regression           | 78.47        | 0.40 |
| K-Nearest Neighbors         | 51.61        | 0.91 |
| Support Vector Regression   | 8.33         | 1.71 |

---

## 🏆 Key Takeaways
- **Random Forest** was the **best model**, outperforming others with the highest accuracy and lowest error.  
- **XGBoost and Decision Tree Regression** were strong contenders, with >90% accuracy.  
- **SVR and KNN** performed poorly for this dataset, highlighting the importance of model selection.  
- Insights into **genres, directors, actors, and temporal trends** can guide movie production and marketing strategies.  

---

## 🚀 Future Work
- Experiment with **deep learning models** for rating prediction.  
- Explore **genre-specific models** (e.g., predicting ratings for only Drama or Action movies).  
- Incorporate **additional metadata** like budgets, release platforms, and international reach.  

---

👨‍💻 Developed as part of the **Data Science Internship at CODSOFT**
