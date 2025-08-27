# 🌸 IRIS Flower Classification

## 📌 Overview
This project focuses on **classifying Iris flower species** using machine learning models.  
It includes:
- Importing necessary libraries  
- Data inspection & visualization  
- Model building  
- Generating predictions  
- Evaluating model performance  

The primary goal of this **multiclass classification project** is to build a robust ML model that can predict the species type of an Iris flower based on its **morphological features**.  

This work enhances the understanding of morphological variations in Iris species and benefits **botanists, researchers, and horticulturists** by improving the ability to categorize and interpret species diversity.

---

## 🎯 Project Details
- **Objective**: Classify Iris flower species using ML models.  
- **Models Used**:  
  - Logistic Regression  
  - K-Nearest Neighbors (KNN)  
  - Gaussian Naive Bayes  
  - Support Vector Machine (SVM)  
  - Decision Tree  
  - Random Forest  

- **Best Model**: K-Nearest Neighbors (KNN)  
- **Performance (KNN)**:  
  - Accuracy: **97%**  
  - Precision: **97.8%**  
  - Recall: **97.3%**  
  - F1-Score: **97.4%**

---

## 🧹 Key Insights
- Dataset is **balanced** → equal records for all three species.  
- **Features**: Four numerical (sepal length, sepal width, petal length, petal width) and one categorical (species).  
- **Exploratory Data Analysis (EDA)** included:  
  - Boxplots, Pairplots, Histograms, Density plots  
  - Swarm plots, Violin plots, Correlation heatmap  
  - Pie chart for species distribution  

- **Findings**:  
  - *Setosa* → most distinguishable due to small feature size.  
  - *Versicolor & Virginica* → often overlap; Versicolor has medium-sized features, Virginica has larger features.  
  - **Petal length & petal width** are the most discriminative features for classification.  

- **ML Models**: Successfully trained multiple classifiers, with **KNN outperforming others** on unseen data.  

---

## 📊 Model Evaluation

| Model                     | Precision | Recall   | F1-score | Accuracy |
|----------------------------|-----------|----------|----------|----------|
| Logistic Regression        | 1.0000    | 1.0000   | 1.0000   | 1.0000   |
| K-Nearest Neighbors (KNN)  | 0.9761    | 0.9737   | 0.9737   | 0.9737   |
| Gaussian Naive Bayes       | 0.9761    | 0.9737   | 0.9737   | 0.9737   |
| Support Vector Machine     | 0.9561    | 0.9474   | 0.9474   | 0.9474   |
| Decision Tree              | 0.9248    | 0.8947   | 0.8930   | 0.8947   |
| Random Forest              | 0.9248    | 0.8947   | 0.8930   | 0.8947   |

---

## 🏆 Best Model
- **K-Nearest Neighbors (KNN)** → Best performing model with **97% accuracy** and strong precision/recall balance.  
- **Logistic Regression** also achieved perfect scores, but KNN showed consistent robustness across multiple test splits.  

---

## 🚀 Future Work
- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV) for further optimization.  
- Deploy the model using **Flask/Streamlit** for interactive predictions.  
- Extend dataset with **real-world flower measurements** for improved generalization.  

---

👨‍💻 Developed as part of the **Data Science Internship at CODSOFT**
