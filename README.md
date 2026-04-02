# breast-cancer-analysis-using-python
Breast cancer prediction using logistic regression, EDA, and visualization in Python
#  Breast Cancer Analysis using Python

##  Project Overview

This project focuses on analyzing a breast cancer dataset and building a machine learning model to classify tumors as **malignant (cancerous)** or **benign (non-cancerous)** using Python.



##  Objectives

* Understand the dataset using Exploratory Data Analysis (EDA)
* Identify important features affecting tumor diagnosis
* Build a machine learning model for classification
* Evaluate model performance using multiple metrics



##  Exploratory Data Analysis (EDA)

* Checked data structure and cleaned dataset
* Analyzed target distribution (benign vs malignant)
* Visualized relationships using heatmaps and plots
* Identified strong correlations between features



## Model Building

* Selected important features based on correlation
* Applied **Logistic Regression** for classification
* Performed train-test split and feature scaling



##  Model Evaluation

* Accuracy: **100%**
* Confusion Matrix: **No misclassifications**
* Classification Report: **Perfect precision, recall, F1-score**
* ROC Curve: **AUC = 1.0 (Excellent performance)**


##  Key Insights

* Features like **radius, perimeter, area, concavity, and symmetry** are strong predictors
* Malignant tumors tend to have more irregular shapes and structures
* The dataset is highly separable, leading to excellent model performance



## Limitations

* 100% accuracy may indicate overfitting or highly separable data
* Model should be tested on new or real-world data for validation



##  Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn



## Files in Repository

* `breast_cancer_analysis.ipynb` → Complete analysis and model
* `breast_cancer_dataset.csv` → Dataset used



## Conclusion

This project demonstrates how machine learning can be effectively used for early detection of breast cancer. The logistic regression model performed exceptionally well, highlighting the importance of tumor characteristics in diagnosis.


