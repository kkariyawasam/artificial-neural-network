# 🧠 Customer Churn Prediction using ANN

This project uses an **Artificial Neural Network (ANN)** to predict customer churn based on structured data from a bank's customer base. It demonstrates data preprocessing, model building using TensorFlow/Keras, and evaluation techniques like confusion matrix and accuracy scores.

---

## 🚀 Project Goals

- Predict if a customer will **leave the bank (churn)**.
- Build a neural network model using TensorFlow/Keras.
- Evaluate performance using metrics and visualizations.

---

## 🧰 Tech Stack

- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **TensorFlow / Keras**

---

## 📊 Dataset

- **Source**: `Churn_Modelling.csv`
- **Features**:
  - CustomerID, Geography, Gender, Age, Tenure, Balance, etc.
- **Target**:
  - `Exited`: 1 (churned), 0 (retained)

> Note: The dataset is not included in the repo due to licensing. You can find it [here](https://www.kaggle.com/datasets/shubhendra7/customer-churn-prediction)

---

## 📌 Workflow

1. **Data Preprocessing**

   - Encoding categorical variables
   - Feature scaling
   - Splitting train and test sets

2. **Model Building**

   - 3-layer ANN with ReLU and Sigmoid activations
   - Optimizer: Adam
   - Loss: Binary Crossentropy

3. **Model Evaluation**
   - Confusion Matrix
   - Accuracy Score
   - Visualization of training loss and accuracy

---

## 📈 Output

- **Accuracy**: ~86%
- **Confusion Matrix**: Displayed using seaborn heatmap
- **Visuals**: Training/validation accuracy and loss plots

---

## 🧠 Learnings

- Built a neural network from scratch using Keras.
- Understood model performance via confusion matrix.
- Learned to preprocess real-world structured data.

---
