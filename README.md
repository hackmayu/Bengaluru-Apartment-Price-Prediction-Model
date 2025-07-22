# 🏙️ **Bengaluru House Price Prediction App**

[![License](https://img.shields.io/github/license/hackmayu/Bengaluru-Apartment-Price-Prediction-Model)](https://github.com/hackmayu/Bengaluru-Apartment-Price-Prediction-Model/blob/main/LICENSE)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![Repo Size](https://img.shields.io/github/repo-size/hackmayu/Bengaluru-Apartment-Price-Prediction-Model)
![Last Commit](https://img.shields.io/github/last-commit/hackmayu/Bengaluru-Apartment-Price-Prediction-Model)
![Stars](https://img.shields.io/github/stars/hackmayu/Bengaluru-Apartment-Price-Prediction-Model?style=social)

---

## 🌟 **Overview**

This project is a **Machine Learning-powered web application** that predicts house prices in Bengaluru, India based on parameters like square footage, number of bedrooms (BHK), bathrooms, and location.

The app uses a **Linear Regression model** built with Python and Scikit-Learn, integrated into a modern web interface using Flask, HTML, CSS, and JavaScript, and deployed using **Nginx on AWS EC2**.

---

## 🌐 **App Preview**

> Example input form where users can estimate price based on area, BHK, bath, and location.

<img width="1919" height="991" alt="Screenshot" src="https://github.com/user-attachments/assets/42697b60-d268-4d31-9b70-02a3a9b076b1" />


---

## 🚀 **Tech Stack**

### 🔧 **Frontend**
- HTML  
- CSS  
- JavaScript  

### 🔗 **Backend**
- Flask (Python microframework)  
- Nginx (Web server / reverse proxy)  
- AWS EC2 (Deployment & hosting)  

### 📊 **ML Model**
- Linear Regression (Scikit-Learn)  

### 🧰 **Libraries Used**
- `pandas` for data preprocessing  
- `numpy` for numerical computations  
- `matplotlib` for data visualization  
- `scikit-learn` for model training and evaluation  

---

## 🎯 **Features**

- 📌 Predict house prices based on user input  
- 🏗️ Clean and responsive web UI  
- 📊 Multiple models tested — Linear Regression selected for best performance  
- 🔄 Real-time integration of ML model into Flask backend  
- ☁️ Deployed using Nginx on AWS EC2 instance  
- 🧹 Data cleaned and preprocessed with outlier handling and one-hot encoding  

---

## 📈 **Model Evaluation**

- Tested several regression models  
- Selected **Linear Regression** based on accuracy and simplicity  
- Used metrics like **R² score**, **MAE**, and visual plots for evaluation  

---

## 📁 **How to Run Locally**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hackmayu/Bengaluru-Apartment-Price-Prediction-Model.git
   cd Bengaluru-Apartment-Price-Prediction-Model
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask app:**
   ```bash
   python app.py
   ```

4. **Open in your browser:**
   ```
   http://127.0.0.1:5000
   ```

---

## 📂 **Dataset**

- Sourced from: [Kaggle – Bengaluru House Price Data](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

---

## 📜 **License**

This project is licensed under the **MIT License**  
(C) 2025 [@hackmayu](https://github.com/hackmayu)

---

## 🙌 **Contributions Welcome**

Pull requests and feature suggestions are welcome.  
Feel free to **fork and build** upon this project!
