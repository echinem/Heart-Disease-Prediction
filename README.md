# ❤️ Heart Disease Prediction Using Machine Learning  
*A Machine Learning Project for Early Heart Disease Risk Classification*

## 📌 Overview  
This project develops a **machine learning–based predictive model** to classify the presence of heart disease using the **UCI Cleveland Heart Disease dataset**. Through systematic data preprocessing, feature selection, model training, and hyperparameter optimization, the project identifies the best-performing model for accurate early diagnosis support.

The final optimized **Random Forest model** achieved:  
- **Accuracy:** 88.52%  
- **ROC-AUC:** 94.37%  
- **High Recall:** 92.86% (minimizing false negatives)

---

## 🧠 Project Objectives  
- Build and evaluate ML classifiers for heart disease prediction  
- Perform extensive EDA and data preprocessing  
- Apply feature selection (Chi-square, ANOVA, Mutual Information)  
- Balance the dataset using **SMOTE**  
- Tune hyperparameters using **GridSearchCV**  
- Compare baseline, SMOTE-enhanced, and tuned models  
- Identify clinically significant features contributing to heart disease prediction  

---

## 📂 Dataset  
**UCI Cleveland Heart Disease Dataset**  
- **Instances:** 303  
- **Features:** 13  
- **Target:** 0 = No disease, 1 = Disease  
- Source: UCI Machine Learning Repository  

---

## 🔧 Technologies & Tools  
- **Programming:** Python 3.x  
- **Libraries:**  
  - pandas, numpy  
  - matplotlib, seaborn  
  - scikit-learn  
  - imbalanced-learn  
  - xgboost  
- **Environment:** Jupyter Notebook  

---

## 🔍 Methodology  
### 1. Exploratory Data Analysis (EDA)  
- Overview of dataset structure  
- Visualization of distributions, correlations, and target imbalance  
- Identification of missing values and outliers  

### 2. Data Preprocessing  
- Median imputation for missing values  
- Outlier capping using **IQR method**  
- StandardScaler for normalization  
- SMOTE for class balancing  

### 3. Feature Selection  
- Chi-Square test  
- ANOVA F-test  
- Mutual Information  
- Key predictors identified: **ca**, **cp**, **thal**, **oldpeak**, **exang**  

### 4. Model Training  
Baseline models evaluated:  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- SVM  
- Naive Bayes  
- AdaBoost  
- XGBoost  

### 5. Hyperparameter Optimization  
- Performed using **GridSearchCV**  
- Tuned models: Random Forest, SVM, XGBoost  

---

## 🏆 Final Model Performance  
**Best Model:** Random Forest (after tuning)  
- **Accuracy:** 88.52%  
- **Precision:** 86.67%  
- **Recall:** 92.86%  
- **F1-Score:** 88.14%  
- **ROC-AUC:** 94.37%  

The model shows excellent discriminative power and strong clinical relevance as a potential decision-support tool.

---

## 📈 Visualizations  
The project generates the following plots:  
- EDA visualizations  
- Correlation heatmap  
- Feature selection comparison  
- Model comparison across metrics  
- Confusion matrix and ROC curve of the best model  

---


