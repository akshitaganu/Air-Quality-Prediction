# 🌫️ Air Quality Index (AQI) Prediction

This project focuses on predicting the Air Quality Index (AQI) using real-world environmental pollutant data collected from various Indian cities. The goal is to build a regression model that accurately forecasts AQI based on concentrations of major air pollutants.

---

## 📌 Project Highlights

- **Data Source**: Used `city_day.csv` from the Central Pollution Control Board (CPCB), covering multiple Indian cities and pollutants.
- **EDA & Preprocessing**:
  - Handled missing values, outliers, and performed normalization.
  - Applied **Yeo-Johnson Transformation** to improve feature distribution.
  - One-hot encoded categorical variables like 'City'.
- **Modeling**:
  - Trained multiple regression models: `Linear Regression`, `Random Forest Regressor`, `Extra Trees Regressor`.
  - Evaluated models using `RMSE`, `R² Score`, and custom accuracy metrics.
  - **Extra Trees Regressor** performed best with **R² ≈ 0.95** and **89% accuracy**.
- **Deployment**:
  - Built an interactive user input tool to predict AQI based on real-time pollutant values.

---

## ⚙️ Tech Stack

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (for modeling and preprocessing)
- Scipy (Yeo-Johnson transformation)
- Jupyter Notebook

---

## 📈 Final Results

| Model                   | RMSE   | R² Score | Accuracy |
|-------------------------|--------|----------|----------|
| Linear Regression       | 39.82  | 0.81     | 72.28%   |
| Random Forest Regressor | 26.47  | 0.92     | 83.19%   |
| Extra Trees Regressor   | 20.43  | 0.95     | 89.10%   |

---

## 📚 Learnings

- Improved understanding of data preprocessing and feature transformation techniques.
- Gained hands-on experience comparing and tuning regression models.
- Learned how to evaluate model performance beyond just accuracy.

