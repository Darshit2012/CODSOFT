# Titanic Survival Prediction

## 📌 Overview
Developed a predictive model to determine survival likelihood on the Titanic dataset.  
Implemented using **Python** with **Pandas, NumPy, Scikit-learn, Seaborn, and XGBoost** for analysis and model development.  

---

## 🎯 Project Objective
To predict the survival probability of passengers aboard the Titanic using multiple classification algorithms and identify the most accurate model.

---

## ⚙️ Models Used
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Bagging  
- AdaBoost  
- Gradient Boosting  
- XGBoost  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Naive Bayes (Gaussian & Bernoulli)  
- Voting Classifier  

---

## 🧹 Key Features
- **Data Preprocessing**: Handled missing values and performed feature engineering.  
- **Normalization**: Standardized the dataset before training.  
- **Model Training**: Applied multiple classification models.  
- **Evaluation**: Compared models using accuracy scores and 10-fold cross-validation.  

---

## 📊 Results

### Accuracy per Model
| Method Used             | Accuracy |
|--------------------------|----------|
| Logistic Regression      | 0.7989   |
| Decision Tree            | 0.7933   |
| Random Forest            | 0.8045   |
| Bagging                  | 0.7989   |
| AdaBoost                 | 0.7933   |
| Gradient Boosting        | 0.7821   |
| XGBoost                  | 0.8156   |
| Support Vector Machine   | 0.8156   |
| K-Nearest Neighbors      | **0.8380** |
| Naive Bayes Gaussian     | 0.7710   |
| Naive Bayes Bernoulli    | 0.7821   |
| Voting Classifier        | 0.8101   |

---

### 10-Fold Cross Validation (Average Accuracies)

| Model                  | Average Accuracy | Std. Dev |
|-------------------------|------------------|----------|
| Decision Tree           | 0.80             | ±0.06    |
| Random Forest           | 0.80             | ±0.07    |
| AdaBoost                | 0.81             | ±0.08    |
| Gradient Boosting       | 0.82             | ±0.06    |
| XGBoost                 | 0.80             | ±0.06    |
| Support Vector Machine  | **0.83**         | ±0.08    |
| K-Nearest Neighbors     | 0.80             | ±0.06    |
| Naive Bayes (Gaussian)  | 0.79             | ±0.08    |
| Naive Bayes (Bernoulli) | 0.78             | ±0.08    |
| Voting Classifier       | 0.82             | ±0.07    |

---

## 🏆 Best Models
- **Support Vector Machine (SVM)** → Highest CV accuracy (**0.83 ± 0.08**)  
- **K-Nearest Neighbors (KNN)** → Best test accuracy (**0.8380**)  

---

## ✅ Final Accuracy Score
**0.8272**

---

👨‍💻 Developed as part of the **Data Science Internship at CODSOFT**
