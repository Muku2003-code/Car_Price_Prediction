# 🚗 Car Price Prediction

This project focuses on building a **machine learning model** to predict **used car prices** based on various features such as year, present price, driven kilometers, fuel type, selling type, transmission, and owner type.

---

## 📌 Project Overview

The project involves the following steps:

1. **Data Loading and Exploration**  
   - Load the dataset  
   - Check structure and missing values  
   - Explore distribution of car prices and feature relationships  

2. **Data Preprocessing**  
   - Encode categorical features into numerical form  

3. **Model Training**  
   - Train two regression models:  
     - Linear Regression  
     - Random Forest Regressor  

4. **Model Evaluation**  
   - Evaluate performance using:  
     - R² Score  
     - Mean Absolute Error (MAE)  
     - Mean Squared Error (MSE)  

5. **Prediction**  
   - Use the trained **Random Forest model** to predict car prices  

6. **Model Saving**  
   - Save the trained Random Forest model for future use  

---

## 📂 Dataset

- **Source:** [Kaggle – Car Price Prediction (Used Cars)](https://www.kaggle.com/datasets/vijayaadithyanvg/car-price-predictionused-cars)  
- **File:** `car data.csv`  
- Contains information about various used cars, including year, price, kilometers driven, fuel type, transmission, and ownership.

---

## 🛠️ Libraries Used

- `pandas` → Data manipulation & analysis  
- `numpy` → Numerical operations  
- `seaborn` & `matplotlib.pyplot` → Data visualization  
- `scikit-learn` → Model training, preprocessing & evaluation  
- `joblib` → Save & load trained models  

---

## 🚀 How to Run the Code

1. Mount **Google Drive** (if using Colab)  
2. Place the dataset (`car data.csv`) in your working directory  
3. Run the Jupyter Notebook step by step  
4. Use the trained model for predictions  

---

## 📊 Model Performance

- **Random Forest Regressor** outperformed **Linear Regression**  
- Evaluation metrics show better accuracy with Random Forest  
- Scatter plot of actual vs predicted prices indicates strong correlation  

---

## 🔮 Future Improvements

- Hyperparameter tuning for Random Forest  
- Explore other regression algorithms  
- Perform deeper feature engineering  
- Conduct more advanced EDA & visualization  

---

## 📁 Project Files

- `car data.csv` → Dataset  
- `car_prediction.json` → Trained Random Forest model  
- `your_notebook_name.ipynb` → Jupyter Notebook with code  

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork this repo and suggest improvements or add new features via pull requests.  

---

## 📜 License

This project is licensed under the **MIT License**.
