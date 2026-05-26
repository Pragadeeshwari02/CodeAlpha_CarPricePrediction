# 🚗💰 Car Price Prediction using Machine Learning

## 📊 Project Overview
This project focuses on building a Machine Learning model that predicts the selling price of used cars based on various features such as:

- 🚘 Car model and age  
- ⛽ Fuel type  
- ⚙️ Transmission type  
- 🛣️ Kilometers driven  
- 👤 Ownership details  
- 💼 Seller type  

Using data analysis, visualization, and Gradient Boosting Regressor, the model learns patterns from historical car data and predicts accurate resale prices.

---

## 🎯 Problem Statement
Predict the selling price of a used car based on its attributes to help buyers and sellers make data-driven pricing decisions.

---

## 📂 Dataset Information
The dataset contains 301 used car records with the following features:

- Car_Name 🚗 → Name/Model of the car  
- Year 📅 → Manufacturing year  
- Selling_Price 💰 → Target variable  
- Present_Price 📊 → Current showroom price  
- Driven_kms 🛣️ → Distance driven  
- Fuel_Type ⛽ → Petrol / Diesel / CNG  
- Selling_type 🏪 → Dealer / Individual  
- Transmission ⚙️ → Manual / Automatic  
- Owner 👤 → Number of previous owners  

---

## 🧹 Data Cleaning & Preprocessing
✔ Removed duplicate records  
✔ Checked and handled missing values  
✔ Converted categorical variables using one-hot encoding  
✔ Created new feature: Car_Age = Current Year - Manufacturing Year  
✔ Dropped unnecessary columns after feature engineering  

---

## 📊 Exploratory Data Analysis (EDA)
We performed EDA using Matplotlib & Seaborn:

📈 Distribution of Selling Price  
🚗 Car Age vs Selling Price  
⛽ Fuel Type vs Price  
⚙️ Transmission vs Price  
🏪 Seller Type vs Price  
🛣️ Driven Kilometers vs Price  
🔥 Correlation Heatmap  

These insights helped understand important price-driving factors.

---

## 🤖 Model Used
### 🌟 Gradient Boosting Regressor

Why Gradient Boosting?
- 🚀 High accuracy  
- 🧠 Learns from previous errors  
- 📉 Reduces bias and variance  
- ⚡ Works well on structured data  

### ⚙️ Model Parameters:
- n_estimators = 300  
- learning_rate = 0.05  
- max_depth = 4  
- random_state = 42  

---

## 📈 Model Performance

- 🎯 R² Score: **0.82**  
- 📉 MAE: **1.02**  
- 📊 RMSE: **2.12**  

✔ The model performs well in predicting used car prices.

---

## 🔮 Sample Prediction

```python
new_car = [[8.5, 35000, 0, 5, 0, 1, 1, 1]]

## 💰 Output:
Predicted Selling Price: ₹ 6.37 Lakhs
```

## 📦 Tech Stack

🐍 Python
📊 Pandas & NumPy
📉 Matplotlib & Seaborn
🤖 Scikit-learn
🌲 Gradient Boosting Regressor

---


## 🚀 How to Run This Project

1️⃣ Clone the repository

```git clone https://github.com/your-username/car-price-prediction.git```

2️⃣ Install dependencies

```pip install -r requirements.txt```

3️⃣ Run the notebook

```jupyter notebook```

---

📌 Project Workflow

Data Collection 📥
↓
Data Cleaning 🧹
↓
EDA 📊
↓
Feature Engineering 🔧
↓
Model Training 🤖
↓
Evaluation 📈
↓
Prediction 🔮

## 💡 Key Insights

🚗 Newer cars have higher resale value
🛣️ More kilometers → lower price
⚙️ Automatic cars often have higher value
⛽ Fuel type impacts pricing significantly

---

## 🏁 Conclusion
This project demonstrates how Machine Learning can predict used car prices effectively. The Gradient Boosting model achieved an R² score of 0.82, showing strong predictive performance.

---

## 🌟 Future Improvements

🔥 Hyperparameter tuning
🌐 Deploy using Flask or Streamlit
📱 Build a web-based price predictor
🧠 Try XGBoost / LightGBM models

---

## 👨‍💻 Author

Pragadeeshwari R R
📧 Email: pragadeeshwarirajkumar@gmail.com
🔗 GitHub: https://github.com/Pragadeeshwari02

---

If you want next level upgrade, I can also make:
🚀 Streamlit web app  
🚀 Professional GitHub banner image  
🚀 Resume project description version  
🚀 LinkedIn post caption for this project  

Just tell me 👍
