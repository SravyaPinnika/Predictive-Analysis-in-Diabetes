# Predictive Analysis in Diabetes

This project focuses on building a predictive model to identify the likelihood of diabetes in patients using machine learning techniques.
The dataset includes various health-related metrics that are used to train a classification model.(Dataset: Kaggle - Pima Indians Diabetes Dataset)

📌 Project Overview

- Goal: To perform predictive analysis on diabetes data using Python and visualize results for better interpretability.
- Dataset: Pima Indians Diabetes Dataset from Kaggle or similar sources.
- Problem Type: Binary classification (Diabetic / Non-Diabetic)


## Tech Stack

- Python (Jupyter Notebook)
- Pandas, NumPy (Data Processing)
- Matplotlib, Seaborn (Data Visualization)
- Scikit-learn (ML Modeling)



##  Project Design

The project was developed in a modular and interpretable manner:

 1. **Data Collection**
   - Dataset imported using Pandas.
   - Basic exploration performed to understand data types, missing values, and feature distribution.

 2. **Data Preprocessing**
   - Handled missing or zero values in health metrics.
   - Data normalization/standardization using Scikit-learn.
   - Label encoding if necessary (though not needed here due to numeric data).

 3. **Exploratory Data Analysis (EDA)**
   - Visualized correlations using heatmaps.
   - Distribution plots for each feature.
   - Boxplots to identify outliers.

 4. **Model Building**
   - Split data into training and testing sets.
   - Trained multiple models:Logistic Regression,K-Nearest Neighbors (KNN),Random Forest Classifier.
   - Evaluated performance using accuracy, confusion matrix, precision, recall.

5. **Model Evaluation**
   - Compared model metrics.
   - Plotted ROC Curves.
   - Chose best-performing model based on evaluation.

 6. **Insights & Conclusion**
   - Highlighted key features affecting diabetes.
   - Discussed future improvements and model deployment options.


## Results

- Achieved good accuracy with Logistic Regression and Decision Tree models.
- Insights from EDA helped in understanding the importance of BMI, glucose, and age in diabetes prediction.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/SravyaPinnika/diabetes-predictive-analysis.git
   cd diabetes-predictive-analysis
