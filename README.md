# 💼 Classification Model Based on Salary Levels

This project focuses on building a classification model to predict whether a person earns more than $50K annually based on demographic attributes. The dataset used is `adult.csv`, which contains demographic and employment-related information of individuals in the U.S.

---

## 📊 Dataset

The dataset contains over 30,000 records with features such as:

- Age
- Workclass
- Education
- Marital-status
- Occupation
- Relationship
- Race
- Sex
- Hours-per-week
- Native-country
- Salary (>50K or <=50K)

---

## 🧠 Objectives

- Clean and preprocess real-world census data  
- Perform exploratory data analysis (EDA)  
- Train and evaluate classification models  
- Compare model performance  
- Identify key factors influencing income prediction  

---

## ⚙️ Technologies Used

- **Python** 🐍  
- **Pandas**, **NumPy** 📦  
- **Matplotlib**, **Seaborn** 📊  
- **Scikit-learn** 🔧  
- **Jupyter Notebook** 📓  

---

## 🛠️ Model Pipeline

### 1. Data Cleaning  
- Removal of missing values and duplicates  
- Encoding categorical variables using label encoding and one-hot encoding  
- Feature selection and correlation analysis  

### 2. Exploratory Data Analysis (EDA)  
- Distribution plots for categorical and numerical variables  
- Correlation heatmaps and feature importance graphs  
- Grouped comparisons by salary levels  

### 3. Model Training  
Trained multiple supervised classification models:  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  

### 4. Evaluation  
Models were evaluated using the following metrics:  
- Accuracy  
- Precision, Recall, F1-score  
- Confusion Matrix  
- ROC-AUC Curve  

---

## ✅ Results

- **Best-performing model**: Random Forest Classifier  
- **Achieved Accuracy**: ~86%  
- **Most Influential Features**:  
  - `education-num`  
  - `hours-per-week`  
  - `occupation`  
  - `age`  
  - `capital-gain`  


