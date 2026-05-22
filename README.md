# 📈 Inflation Rate Prediction of India

## 📌 Project Overview

This project predicts India's inflation rate using Machine Learning techniques and macroeconomic indicators. Multiple regression models were implemented and compared to analyze their prediction performance and reliability.

---

## 📊 Dataset Features

- Year
- Month
- Brent Oil Price (USD/barrel)
- USD to INR Exchange Rate
- Repo Rate
- Petrol Price
- Rainfall

### 🎯 Target Variable
- Inflation Rate (%)

---

## ⚙️ Models Used

- Linear Regression
- Ridge Regression
- K-Nearest Neighbors (KNN)
- Random Forest Regressor

---

## 📈 Model Performance

| Model | R² Score | RMSE | MAE | Performance |
|---|---|---|---|---|
| Linear Regression | 0.174 | 1.562 | 1.290 | Poor |
| Ridge Regression | 0.138 | 1.595 | 1.332 | Poor |
| KNN Regressor | 0.568 | 1.129 | 0.835 | Good |
| Random Forest | 0.690 | 0.948 | 0.736 | Best |

---

## 🔍 Key Observations

- Inflation data showed nonlinear patterns, reducing Linear Regression performance.
- Ridge Regression improved model stability using regularization.
- KNN performance improved after feature scaling using StandardScaler.
- Random Forest achieved the highest accuracy and lowest prediction error.
- Correlation analysis helped identify relationships between economic indicators and inflation rate.
- Boxplots were used to detect outliers and analyze data spread.

---

## 🔮 Future Prediction

The trained models were tested using future economic input values for inflation forecasting.

- Linear & Ridge models produced less accurate predictions.
- KNN showed moderate prediction performance.
- Random Forest produced the most stable and reliable predictions.

---

## ✅ Conclusion

Random Forest Regressor achieved the best performance with the highest R² score and lowest RMSE and MAE values. The project demonstrates how macroeconomic indicators can be used for inflation forecasting using Machine Learning techniques.

---

## 🚀 Future Improvements

- Add larger economic datasets
- Apply Time Series forecasting models
- Perform hyperparameter tuning
- Deploy model using Flask or Streamlit

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Project Structure

- `inflation_prediction.ipynb`
- `inflation_dataset.csv`
- `README.md`
- `requirements.txt`
- `images/`

---

## 👨‍💻 Author

**Sisir Pradhan**