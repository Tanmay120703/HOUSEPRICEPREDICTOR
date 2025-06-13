# HOUSEPRICEPREDICTOR
# 🏠 Housing Price Prediction using Artificial Neural Network (ANN) in PyTorch

This project implements an end-to-end deep learning pipeline using PyTorch to predict housing prices based on structured features. It covers everything from data preprocessing, model building, training, evaluation, and prediction on new data.

---

## 📁 Dataset

The dataset used is `Housing.csv`, containing the following features:

- **Numerical:** area, bedrooms, bathrooms, stories, parking
- **Categorical:** mainroad, guestroom, basement, hotwaterheating, airconditioning, prefarea, furnishingstatus
- **Target:** price

---

## ✅ Features

- Categorical feature encoding using `OneHotEncoder`
- Standard scaling of both features and target
- PyTorch `Dataset` and `DataLoader` for efficient batching
- ANN model built using `torch.nn.Sequential`
- Training loop with MSE loss and Adam optimizer
- Evaluation using RMSE, MAE, and R² Score
- Easy prediction on new data

