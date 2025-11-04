# 🚗 Automobile Price Predictor

A **machine learning-powered Streamlit web app** that predicts automobile prices based on key features such as make, body style, horsepower, and weight. The app uses trained encoders and a regression model to provide accurate, data-driven price forecasts — helping users make smarter buying or selling decisions in the auto market.

---

## 📘 Project Overview
The project leverages machine learning algorithms to forecast vehicle prices using historical data. It analyzes factors like brand, model, mileage, and specifications to predict an automobile’s market value. Built with **Python**, **Streamlit**, and **scikit-learn**, this app demonstrates how data-driven insights can enhance decision-making in the automotive industry.

---

## 🧠 Features
- User-friendly Streamlit interface  
- Real-time automobile price prediction  
- Encoded categorical features (`make`, `body-style`)  
- Data visualization and input display  
- Pre-trained ML model integration using `joblib`  

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:** pandas, scikit-learn, joblib, streamlit  
- **Model:** Trained regression model (`autoMobilePredmodel.pkl`)  
- **Encoders:** Label encoders for `make` and `body-style`

---

## 🚀 How to Run the App
1. Clone the repository:
   ```bash
   git clone https://github.com/Headmaster-22/Automobile-Price-Predictor.git
   cd Automobile-Price-Predictor


2. Install dependencies:
pip install -r requirements.txt

3. Run the Streamlit app:
    ```bash
    streamlit run automobile_app.py

## 📁 Requirements
pandas
numpy
scikit-learn
joblib
streamlit


## Built by Headmaster22