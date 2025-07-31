# Used Car Price Prediction

This project aims to build a machine learning model that predicts the resale price of used cars based on key features such as year, mileage, fuel type, transmission, power, engine capacity, and ownership type. It demonstrates an end-to-end ML workflow including data cleaning, feature engineering, model comparison, and evaluation.

---

## Problem Statement

Accurately estimating the resale value of used cars is essential for both buyers and sellers. Prices vary significantly depending on the vehicle’s condition, specifications, and usage. In this project, we use machine learning techniques to develop a regression model that can predict the selling price of a used car based on historical data.

---

## Dataset

- Source: https://www.kaggle.com/datasets/avikasliwal/used-cars-price-prediction/data?select=train-data.csv
- Rows: 6,000+ entries
- Features: Car model, year, mileage, engine, power, fuel type, owner type, transmission, etc.
- Target variable: `Price` (resale value in lakhs)

---

## 🛠Technologies Used

- Python
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib

---

## ML Models Implemented

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Each model was evaluated using:
- R² Score
- Mean Squared Error (MSE)
- Cross-validation

---

## Key Steps

- Exploratory Data Analysis (EDA)
- Data cleaning (handling missing values, type conversion)
- Feature engineering (e.g., car age)
- Model training and evaluation
- Overfitting/underfitting analysis
- Visualizations for interpretation

---

## Results

- Best model: *e.g., Random Forest Regressor*
- R² Score: *e.g., 0.89*
- MSE: *e.g., 1.2 lakhs²*

---

## Future Improvements

- Use more advanced models (LightGBM, CatBoost)
- Deploy as a Flask web app
- Integrate with a real-time price lookup API

---

## Project Structure

used-car-price-prediction/
│
├── notebook.ipynb # Jupyter notebook with full workflow
├── train-data.csv # Dataset
├── README.md # Project summary and documentation


---

## Author

**Sai Sahi Majji**  
[LinkedIn](www.linkedin.com/in/sai-sahi-ml-ai) | [GitHub](https://github.com/SahiMLE)

---

## 📜 License

This project is open-source and free to use under the MIT License.


