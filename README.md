# L.-R-ANALYSIS
Linear Regression Analysis
ME
# 🧠 Machine Learning Classification of White Wine Quality

This project implements and compares three machine learning models to classify white wine quality using the *Wine Quality (White)* dataset. The task is framed as a **binary classification problem**, where wines with a quality score ≥6 are labelled as **"good"**, and those <6 as **"bad"**.

The project evaluates traditional machine learning models alongside a neural network, analysing their performance across multiple configurations.

---

## 📄 Project Overview

The dataset contains **4,898 observations** and **12 attributes**, including physicochemical properties such as acidity, pH, alcohol level, and residual sugar.

Three models were implemented:

- **Logistic Regression**
- **Random Forest Classifier**
- **MLPClassifier (Neural Network)**

Each model was tested under **three different configurations**, producing a total of **nine sets of results**.

---

## 🎯 Objective

The goal of this project is to:

- Build and compare multiple classification models  
- Evaluate their performance using standard metrics  
- Identify which model performs best  
- Analyse which features contribute most to wine quality prediction  

---

## 📊 Dataset

- **Name:** Wine Quality – White  
- **Source:** UCI Machine Learning Repository  
- **Samples:** 4,898  
- **Features:** 11 physicochemical variables + quality score  
- **Task:** Binary classification (good vs bad wine)

---

## 🧪 Models Implemented

### 1. Logistic Regression  
A baseline linear model used to establish a reference performance.

### 2. Random Forest Classifier  
An ensemble model based on decision trees, robust to non-linear relationships.

### 3. MLPClassifier  
A feed-forward neural network capable of modelling complex patterns.

---

## 📈 Evaluation Metrics

Each model was evaluated using:

- **Accuracy**
- **F1-score**
- **Confusion Matrix**

(Your lecturer recommended including exact metric values rather than approximations.)

---

## 🧠 Key Findings

- All required sections were implemented and clearly presented.  
- The project successfully compared nine model configurations.  
- The analysis provided meaningful interpretation of results.  
- The submission was evaluated positively by the lecturer.  
- Future improvement: report **exact metric values** instead of approximate ones.

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook / VSCode  

---

## 📂 Repository Structure

```
├── L.Regr.R.For.MLP.ipynb
├── Metrics.ipynb
├── winequality-white.csv
├── README.md
```

---

## 🚀 How to Run

1. Clone the repository  
2. Install required Python libraries  
3. Open the notebooks in VSCode or Jupyter  
4. Run the cells in order to reproduce the results  

---

## 📚 Academic Context

This project was submitted as part of an academic assignment and received positive feedback, noting strong structure, clear interpretation, and correct implementation of the required models and evaluations.

