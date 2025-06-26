
# 🧠 Customer Behavior Prediction Projects using ANN

This repository contains two machine learning projects that utilize **Artificial Neural Networks (ANNs)** to model customer behavior. Both projects involve data preprocessing, ANN model construction using **TensorFlow/Keras**, and performance evaluation through relevant metrics and visualizations.

---

## 🚗 Project 1: Car Purchase Amount Prediction

### 🎯 Objective  
Develop a regression model using an ANN to **predict the total dollar amount a customer is willing to pay for a car** based on their personal and demographic information.

### 📄 Dataset  
- Contains features such as **Gender, Age, Annual Salary, Credit Card Debt**, and **Net Worth**.
- Target variable: **Car Purchase Amount** (continuous value).

### 🧰 Workflow  
1. **Data Preprocessing**
   - Handling numerical and categorical features
   - Feature scaling
   - Train-test split

2. **Model Building**
   - ANN with multiple dense layers
   - Activation functions: ReLU (hidden layers), Linear (output)
   - Loss: Mean Squared Error (MSE)
   - Optimizer: Adam

3. **Evaluation**
   - Loss and MAE metrics
   - Visualizations: Training/validation loss plots

### ✅ Outcome  
- Successfully trained a regression ANN model.
- Able to predict car purchase amounts with reasonable accuracy.
- Learned how ANNs handle continuous output prediction.

---

## 🔁 Project 2: Customer Churn Prediction

### 🎯 Objective  
Use ANN to **predict whether a customer will leave the bank (churn)** using structured customer data.

### 📄 Dataset  
- Source: `Churn_Modelling.csv`
- Features: **Geography, Gender, Age, Tenure, Balance, Estimated Salary**, etc.
- Target variable: `Exited` (1 = churned, 0 = retained)

### 🧰 Workflow  
1. **Data Preprocessing**
   - Label encoding and one-hot encoding
   - Feature scaling
   - Train-test split

2. **Model Building**
   - ANN with 3 layers
   - Activation functions: ReLU (hidden layers), Sigmoid (output)
   - Loss: Binary Crossentropy
   - Optimizer: Adam

3. **Evaluation**
   - Accuracy Score
   - Confusion Matrix
   - Visualizations: Accuracy and loss trends

### ✅ Outcome  
- **Model Accuracy**: ~86%
- Visual understanding of training performance
- Clear insight into the bank’s churn patterns

---

## 🧰 Common Tech Stack

- Python, Jupyter Notebook  
- Pandas, NumPy, Matplotlib, Seaborn  
- Scikit-learn  
- TensorFlow / Keras  

---

## 🧠 Learnings

- Gained hands-on experience in building and evaluating ANN models.
- Understood differences between regression and classification use-cases with neural networks.
- Practiced real-world data preprocessing and visualization techniques.
