

Laptop Price Prediction using Machine Learning

##  Project Overview

The **Laptop Price Prediction** project aims to predict the price of a laptop based on its specifications such as RAM, processor speed, storage capacity, screen size, and weight.

This project uses Machine Learning algorithms to analyze patterns between laptop features and their prices, helping users estimate a laptop’s cost accurately.

---

## 🎯 Problem Statement

Laptop prices vary depending on specifications and brand.
It is difficult to manually estimate the correct price.

This project builds a regression model that predicts the price based on laptop features.

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Streamlit
* Pickle

---

## 📂 Project Structure

```
Laptop-Price-Prediction/
│
├── Laptop_price.csv
├── ml.ipynb
├── app.py
├── model.pkl
├── scaler.pkl
├── encoders.pkl
├── requirements.txt
└── README.md
```

---

## 🔎 Machine Learning Workflow

### 1️⃣ Data Loading

* Dataset loaded using Pandas.

### 2️⃣ Data Preprocessing

* Handled missing values
* Removed duplicates
* Converted categorical variables into numerical values
* Feature scaling using StandardScaler

### 3️⃣ Feature Selection

* Independent Variables (X)
* Target Variable (y → Price)

### 4️⃣ Model Training

Models Used:

* Linear Regression
* Support Vector Machine (SVM)
* Decision Tree Regressor
* Random Forest Regressor
* Polynomial Regression

### 5️⃣ Model Evaluation

Evaluation Metrics:

* MAE (Mean Absolute Error)
* MSE (Mean Squared Error)
* RMSE
* R² Score

### 6️⃣ Model Saving

* Model saved using Pickle
* Scaler saved
* Encoders saved

---

## 🧠 Best Performing Model

Random Forest Regressor performed best with higher R² score and lower error metrics.

---

## 🚀 How to Run the Project

### 🔹 Step 1: Clone Repository

```bash
git clone <your-repo-link>
cd Laptop-Price-Prediction
```

### 🔹 Step 2: Create Virtual Environment (Recommended)

```bash
python -m venv .venv
.venv\Scripts\activate
```

### 🔹 Step 3: Install Requirements

```bash
pip install -r requirements.txt
```

If requirements.txt not available:

```bash
pip install streamlit pandas numpy scikit-learn matplotlib seaborn
```

### 🔹 Step 4: Run Streamlit App

```bash
streamlit run app.py
```

---

## 💻 Streamlit Web App Features

* User-friendly UI
* Input laptop specifications
* Real-time price prediction
* Scaled and encoded inputs automatically
* Displays predicted laptop price in ₹

---

## 📊 Sample Input Features

* Brand
* Processor Speed (GHz)
* RAM Size (GB)
* Storage Capacity (GB)
* Screen Size (inches)
* Weight (kg)

---

## 📈 Model Performance Metrics Example

| Metric | Value |
| ------ | ----- |
| MAE    | Low   |
| RMSE   | Low   |
| R²     | High  |

---

## 🔮 Future Improvements

* Use OneHotEncoding instead of LabelEncoding
* Hyperparameter tuning
* Add cross-validation
* Deploy on Streamlit Cloud
* Add comparison charts
* Add feature importance visualization

---

## 📌 Author

**Bhavanasri**
Machine Learning Enthusiast
Python Developer

---

## ⭐ Conclusion

This project demonstrates:

* End-to-end Machine Learning pipeline
* Data preprocessing techniques
* Model training and evaluation
* Model deployment using Streamlit

It can be used as a beginner-to-intermediate level ML portfolio project.

---

Tell me what you want next 🚀
