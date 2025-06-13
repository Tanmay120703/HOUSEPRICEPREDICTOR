# 🏠 Housing Price Prediction using PyTorch

This project builds an Artificial Neural Network (ANN) using PyTorch to **predict housing prices** based on features like location, area, number of bedrooms, and amenities. It is a **regression** problem.

---

## 🗂️ Project Files

- `Housing_Price_Prediction.ipynb`: Jupyter notebook with the full end-to-end pipeline.
- `Housing.csv`: Dataset used for training and testing.
- `requirements.txt`: Dependencies for this project.

---

## 🧾 Objective

To predict the **price of a house** using various features such as:
- Area
- Bedrooms
- Bathrooms
- Furnishing status
- Location
- Parking availability

---

## ⚙️ Tech Stack

- **Language:** Python
- **Framework:** PyTorch
- **Data Handling:** Pandas, NumPy
- **Preprocessing:** Scikit-learn (OneHotEncoder, StandardScaler)
- **Evaluation:** MSE, MAE, R² score

---

## 🔁 Pipeline Overview

1. **Data Loading**
2. **Categorical/Numerical Feature Separation**
3. **Column Transformation** (OneHot + Standard Scaling)
4. **Train-Test Split**
5. **DataLoader + Custom Dataset**
6. **ANN Architecture**:
   - Linear Layers, ReLU, Dropout, BatchNorm
7. **Training Loop** with `MSELoss`
8. **Validation** using R², MAE, RMSE
9. **Predict on New Data**

---

## 📦 Installation

```bash
pip install -r requirements.txt
