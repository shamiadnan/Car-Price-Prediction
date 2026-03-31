# 🚗 Car Price Prediction – Machine Learning Project

## 📌 Overview
This project applies machine learning regression techniques to predict the resale value of cars.  
The system estimates selling prices based on features such as fuel type, years of service, showroom price, number of previous owners, kilometers driven, seller type, and transmission type.  
It demonstrates an end‑to‑end ML workflow: data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment with a user‑friendly interface.

---

## 📊 Dataset
The dataset contains historical car sales records with attributes:
- **Year** – manufacturing year of the car  
- **Present Price** – showroom price in lakhs  
- **Kms Driven** – total kilometers driven  
- **Owner** – number of previous owners  
- **Fuel Type** – Petrol, Diesel, or CNG  
- **Seller Type** – Dealer or Individual  
- **Transmission** – Manual or Automatic  

Derived features include **Years of Service** and one‑hot encoded categorical variables.

---

## ⚙️ Workflow
1. **Data Preprocessing**  
   - Handle missing values  
   - Encode categorical variables  
   - Feature scaling and feature engineering  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots  
   - Correlation heatmaps  
   - Feature importance visualization  

3. **Model Training**  
   - Linear Regression  
   - Decision Tree  
   - Random Forest (selected as best performing)  

4. **Result Analysis**  
   - Metrics: R² Score, Mean Absolute Error (MAE)  
   - Comparison of models to select the most accurate  

5. **Deployment**  
   - Save trained model as `.pkl`  
   - Load model in Gradio  
   - Build interactive interface for predictions  

---

## 📈 Visualizations
- Correlation heatmap to identify relationships between features  
- Feature importance plots from Random Forest  
- Predicted vs Actual price comparison charts  
- Distribution plots for key variables (Price, Kms Driven, Years of Service)  

---

## 📊 Result Analysis
- **Linear Regression**: Simple baseline, limited accuracy  
- **Decision Tree**: Better fit but prone to overfitting  
- **Random Forest**: Best performance with balanced accuracy and generalization  
- Final model chosen: **Random Forest**, due to superior R² and lower MAE  


https://github.com/user-attachments/assets/d8d124d2-a653-47c8-9380-9e686858b4d3
 ![dfe042f4-529d-4d8a-b20f-d1f93ebdd95e](https://github.com/user-attachments/assets/bb0803bf-9b64-4d2d-87db-2a98e6eb73c2)
![4a85cbd3-32be-4e48-8c![52103e39-12ef-476a-b4c5-3982acf6431e](https://github.com/user-attachments/assets/c3b32e8e-f10f-4c70-8a54-907572d20b38)
69-0942c0ea1619](https://gith![9d5cc990-6655-4a1e-8292-ac8936eabe12](https://github.com/user-attachments/assets/7c3aef94-4cc2-4c49-bacf-9a2e58f6d794)
![63540699-07c4-4ee6-b2c3-824e21199cde](https://github.com/user-attachments/assets/e0420a14-6f28-4e89-86ac-074bb8f61c46)
ub.com/user-attachments/assets/7952e0cb-9afc-4a93-887e-39219597cbcc)

---

## 🚀 Live Demo
The project integrates **Gradio** to provide an interactive web interface.  
Users can input car details (year, price, kms driven, owners, fuel type, seller type, transmission) and instantly receive an approximate selling price prediction.

To run the app:
URL - https://16ee367a939eff6586.gradio.live/

---

## 👨‍💻 Author
Developed by Adnan 
