# 🏥 Medical Insurance Amount Prediction

This project predicts **medical insurance charges** based on key personal and lifestyle factors such as age, BMI, smoking habits, gender, and region. It applies machine learning techniques to estimate the expected insurance cost for an individual.

The goal of this project is to demonstrate end-to-end ML workflow skills including data preprocessing, EDA, model building, visualization, and evaluation.

---

## 📘 Problem Statement

Insurance companies determine premium amounts using customer demographic and health data.  
This project predicts **medical insurance charges** using machine learning so that:

- Individuals can estimate expected insurance costs  
- Companies can identify cost-driving factors  
- ML learners can understand regression-based prediction models  

---

## 📂 Dataset Details

The dataset contains the following features:

| Feature | Description |
|--------|-------------|
| **age** | Age of the individual |
| **sex** | Male/Female |
| **bmi** | Body Mass Index |
| **children** | Number of dependents |
| **smoker** | Smoking status |
| **region** | Residential region |
| **charges** | Medical insurance cost (Target variable) |

---

## 🧪 Exploratory Data Analysis (EDA)

The notebook includes:

- Distribution plots for `age`, `bmi`, and `charges`
- Pairplots to identify trends  
- Correlation heatmap  
- Comparison between smokers vs non-smokers  
- Outlier detection (especially BMI & charges)

Key insights include:

- **Smokers have significantly higher insurance charges**
- **BMI strongly impacts charges for smokers**
- **Age is positively correlated with charges**

---

## 🧠 Machine Learning Approach

### ✔ Models Implemented
- **Linear Regression** (Primary model)
- Encoding of categorical variables
- Train-test split
- Feature scaling where necessary

### ✔ Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

These metrics help measure the accuracy and performance of the model.

