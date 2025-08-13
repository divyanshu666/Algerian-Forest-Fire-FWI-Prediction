# 🌲 Algerian Forest Fire Dataset – FWI Prediction

This project predicts the **Fire Weather Index (FWI)** using the **Algerian Forest Fire dataset**.  
It involves **data cleaning, exploratory data analysis (EDA)**, feature selection, and training multiple machine learning models to find the best predictor.  
The best-performing model (**Ridge Regression**) achieved an **R² score of 98%**, and was deployed using **Flask** on **AWS Elastic Beanstalk** with a CI/CD pipeline via **GitHub Oauth App**.

---

## 📌 Project Workflow

### 1️⃣ Data Preprocessing
- **Data Cleaning & EDA**: Handled missing values, outliers, and formatted dataset.
- **Multicollinearity Check**: Used **correlation matrix** to detect and remove highly correlated features.
- **Feature Selection**: Selected the most impactful variables for prediction.

### 2️⃣ Model Building
- Trained models:
  - Linear Regression
  - Lasso Regressor
  - ElasticNet Regressor
  - Ridge Regression
- **Best Model**: Ridge Regression with R² = **98%**
- Saved the trained **scaler** and **Ridge Regression model** as `.pkl` files.

### 3️⃣ Deployment
- Built a **Flask API** to serve the model.
- Deployed on **AWS Elastic Beanstalk**.
- Set up **AWS CodePipeline** for automated deployment via **GitHub**.

---

## 🛠 Tech Stack

**Programming Language:**  
- Python

**Libraries Used:**
- `Flask`
- `NumPy`
- `pandas`
- `scikit-learn`
- `seaborn`
- `matplotlib`

**Deployment:**
- AWS Elastic Beanstalk
- AWS CodePipeline (CI/CD)
- GitHub Oauth App

---

