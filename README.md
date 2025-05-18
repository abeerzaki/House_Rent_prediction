# 🏡 House Rent Prediction

This project aims to predict house rental prices based on features like size, location, furnishing status, and more, using machine learning models. It also uses SHAP (SHapley Additive Explanations) for model interpretability.

---

## 📂 Project Structure

- `data/` — Raw and cleaned dataset 
- `notebooks/` — Jupyter notebook(s) with full analysis and modeling steps
- `README.md` — Project documentation

---

## 📊 Features Used

- BHK
- Size
- Bathroom
- Furnishing Status
- City
- Area Type
- Floor
- Tenant Preference
- Month, Day, and Weekday of Posting
- Point of Contact

---

## 🧠 Models Used

- Linear Regression
- Random Forest
- Gradient Boosting
- XGBoost
- LightGBM
- CatBoost
- ANN (Keras)

---

## ✅ Evaluation Metrics

- **RMSE (Root Mean Squared Error)**
- **R² Score**
- Comparison before and after applying:
  - `log1p` transformation
  - `StandardScaler`


---

## 🔍 Model Interpretation

SHAP was used to explain:
- Global feature importance
- Individual prediction explanations
- Feature impact on model output

---

## 🚀 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/abeerzaki/House_Rent_prediction.git
