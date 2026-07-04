# 🌸 Iris Flower Classification - Machine Learning Project

## 📌 Project Overview
This project is a simple **Machine Learning classification model** that predicts the type of Iris flower based on its features such as:
- Sepal length
- Sepal width
- Petal length
- Petal width

The model uses **Logistic Regression** to classify flowers into three categories:
- Setosa
- Versicolor
- Virginica

This project demonstrates the basic ML workflow including data preprocessing, model training, evaluation, and prediction.

---

## 🧠 Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## ⚙️ Steps Involved

### 1️⃣ Load Dataset
We use the built-in Iris dataset from sklearn.

### 2️⃣ Data Preprocessing
- Convert dataset into DataFrame
- Split features and target variable

### 3️⃣ Train-Test Split
- 80% training data
- 20% testing data

### 4️⃣ Feature Scaling
- StandardScaler is used to normalize data

### 5️⃣ Model Training
- Logistic Regression model is trained on the dataset

### 6️⃣ Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

### 7️⃣ Prediction
- Predicts flower type for new input data

---

## 📊 Results


## 📊 Output

### Dataset Preview
   sepal length (cm)  sepal width (cm)  petal length (cm)  petal width (cm)  target
0                5.1               3.5                1.4               0.2       0
1                4.9               3.0                1.4               0.2       0
2                4.7               3.2                1.3               0.2       0
3                4.6               3.1                1.5               0.2       0
4                5.0               3.6                1.4               0.2       0


- ✅ Accuracy: ~95% - 100% (depends on split)
- ✅ Model performs very well on small dataset
- ✅ Correct classification of most test samples

Model Evaluation
Accuracy: 1.0

📌 Confusion Matrix
[[10  0  0]
 [ 0  9  0]
 [ 0  0 11]]
 
📌 Classification Report
              precision    recall  f1-score   support

           0       1.00      1.00      1.00        10
           1       1.00      1.00      1.00         9
           2       1.00      1.00      1.00        11

    accuracy                           1.00        30


    
🌸 Final Prediction
Predicted Flower: setosa




