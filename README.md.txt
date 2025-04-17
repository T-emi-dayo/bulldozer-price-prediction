# 🚜 Bulldozer Price Prediction

🔹 **Objective:** Predict the sale price of used bulldozers based on historical data.  
🔹 **Dataset:** [Kaggle - Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers)  
🔹 **Tech Stack:** Python, Pandas, Scikit-Learn, , Matplotlib  

---

## 📌 1. Overview  
In the construction industry, knowing the **right price of used equipment** is crucial.  
This project applies **Machine Learning** to predict bulldozer prices based on past sales data.  

---

## 📌 2. Dataset  
- **Source:** [Kaggle Bulldozer Dataset](https://www.kaggle.com/c/bluebook-for-bulldozers/data)  
- **Features:** Equipment type, sale date, year made, usage hours, etc.  
- **Target Variable:** `SalePrice` (What we aim to predict)  

---

## 📌 3. Exploratory Data Analysis (EDA)  
✔ Checked for missing values & outliers  
✔ Visualized trends in bulldozer prices over time  
✔ Identified key features influencing price  


---

## 📌 4. Model Training  
| Model                | RMSLE Score |
|----------------------|------------|
| XGBoost              | 0.258     |
| Random Forest        | 0.243     |

🚀 **Best Model:** Random Forest (RMSE = 0.243)  

---


## 📌 5. Next Steps  
🔹 Hyperparameter tuning for better accuracy  
🔹 Deploy a live model with an interactive UI  
🔹 Try deep learning models (e.g., TensorFlow)  

---

## 📌 6. How to Use  
Clone this repo & install dependencies:  
```bash
git clone https://github.com/your-username/bulldozer-price-prediction.git
cd bulldozer-price-prediction
pip install -r requirements.txt
