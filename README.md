# # 🏠 Housing Price Prediction using Linear Regression

This Jupyter Notebook demonstrates the implementation of **Simple** and **Multiple Linear Regression** models using the `Housing.csv` dataset.

---

## 📁 Dataset

The dataset contains housing features such as:
- `area`, `bedrooms`, `bathrooms`, `stories`, `parking`
- Categorical: `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `furnishingstatus`
- Target: `price`

---

## 📌 Steps Performed

1. **Data Loading & Preprocessing**
   - Handled categorical features using One-Hot Encoding.
2. **Train-Test Split**
   - 80% training, 20% testing.
3. **Multiple Linear Regression**
   - Evaluated with MAE, MSE, and R² score.
   - Interpreted model coefficients.
4. **Simple Linear Regression**
   - Visualized the relationship between `area` and `price`.

---

## 📊 Results (Example)

- **MAE**: ₹970,043.40
- **MSE**: ₹1.75 × 10¹²
- **R² Score**: 0.653
- **Highest Impact Features**:
  - `bathrooms`, `airconditioning`, `hotwaterheating`, `prefarea`

---

## 🧪 Requirements

Install with:
pip install -r requirements.txt
